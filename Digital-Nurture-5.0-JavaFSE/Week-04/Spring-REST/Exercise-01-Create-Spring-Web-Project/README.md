# Create Spring Boot Web Project Exercise

## Objective
This exercise bootstraps a basic Spring Boot MVC web application.

## Implementation
### Project Files
* `application.properties` – H2 database and port property setups
* `pom.xml` – Maven file containing dependencies and build settings
* `SpringLearnApplication.java` – Spring Boot main application class
* `SpringLearnApplicationTests.java` – Integration tests validating web server boots

### Implementation Details
I created a Spring Boot application class using web starter configurations in pom.xml.

## How to Run
```bash
mvn clean test
```

## Expected Output
The application starts the Tomcat web server and starts the application context .

### Key Takeaways
I learned how Spring Boot handles automatic configuration for web projects.
