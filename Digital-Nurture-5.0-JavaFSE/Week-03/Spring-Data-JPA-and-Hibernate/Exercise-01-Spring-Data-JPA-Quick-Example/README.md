# Spring Data JPA CRUD Exercise

## Objective
In this exercise, I worked on basic database operations using Spring Data JPA and H2 database.

## Implementation
### Project Files
* `application.properties` – H2 database and port property setups
* `Country.java` – JPA Country entity class
* `CountryNotFoundException.java` – custom exception used when a record is not found
* `CountryRepository.java` – JPA Country database repository interface
* `CountryService.java` – service class for database operations
* `data.sql` – SQL seeding queries script
* `OrmLearnApplication.java` – Spring Boot application main class
* `OrmLearnApplicationTests.java` – JPA CRUD transaction integration test
* `pom.xml` – Maven file containing dependencies and build settings

### Implementation Details
I created a JPA entity with annotations, extended JpaRepository, and configured an in-memory H2 connection.

## How to Run
```bash
mvn clean test
```

## Expected Output
The application starts, seeds data from data.sql, and runs CRUD queries using JPA.

### Key Takeaways
I learned how Spring Data JPA reduces repeated database code.
