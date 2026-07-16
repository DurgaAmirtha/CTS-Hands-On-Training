# Spring XML Configuration Exercise

## Objective
In this exercise, I worked on basic Spring configurations. It declares core beans in an XML context.

## Implementation
### Project Files
* `applicationContext.xml` – Spring XML file containing bean definitions
* `BookRepository.java` – Data access repository bean class
* `BookService.java` – Business service bean class
* `LibraryManagementTest.java` – test class for loading the Spring context
* `pom.xml` – Maven file containing dependencies and build settings

### Implementation Details
I defined BookRepository and BookService beans inside applicationContext.xml and loaded the application context.

## How to Run
```bash
mvn clean test
```

## Expected Output
The test loads the context, instantiates the repository and service beans, and verifies they are active.

### Key Takeaways
I learned how Spring IoC manages bean creation through XML configurations.
