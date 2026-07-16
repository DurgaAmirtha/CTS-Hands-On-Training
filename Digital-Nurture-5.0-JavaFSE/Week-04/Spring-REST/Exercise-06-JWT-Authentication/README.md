# JWT REST API Security Exercise

## Objective
This exercise secures REST API endpoints using role-based controls and JWT tokens.

## Implementation
### Project Files
* `application.properties` – H2 database and port property setups
* `AuthenticationController.java` – Controller handling security tokens and authentication checks
* `Country.java` – JPA Country entity class
* `country.xml` – Spring XML resource seeding country database records
* `CountryController.java` – Controller mapping REST routes for countries metadata
* `CountryNotFoundException.java` – custom exception used when a record is not found
* `CountryService.java` – service class for database operations
* `HelloController.java` – Controller mapping hello REST routes
* `JwtAuthorizationFilter.java` – Security filter parsing Bearer headers validation tokens
* `pom.xml` – Maven file containing dependencies and build settings
* `SecurityConfig.java` – Web security configuration bean definition mappings
* `SpringLearnApplication.java` – Spring Boot main application class
* `SpringLearnApplicationTests.java` – Integration tests validating web server boots

### Implementation Details
I implemented basic authentication for token exchange and a custom JWT filter to authorize subsequent requests.

## How to Run
```bash
mvn clean test
```

## Expected Output
The application creates JWT tokens for valid requests and authorizes subsequent API calls.

### Key Takeaways
I learned how to build and secure REST APIs using custom filters and tokens in Spring Boot.
