# Resume Analyzer

A Java web app for uploading and analyzing resumes, scoring skills, and checking resume quality.

## Features
- Resume upload
- PDF text extraction
- Skill scoring and suggestions
- Admin login and dashboard
- Java EE / Jakarta EE web app

## Run locally

```bash
mvn clean package
```

Then deploy the generated WAR file in a Java servlet container such as Tomcat.

## Project structure
- `src/main/java` — Java servlets and logic
- `src/main/webapp` — JSP pages
- `pom.xml` — Maven configuration

## Requirements
- Java 17+
- Maven
- Tomcat or another Jakarta-compatible server
- MySQL (for DB-backed features)
