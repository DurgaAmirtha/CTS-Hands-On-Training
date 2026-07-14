# Spring Setter Injection

## About the Exercise
In this exercise, I worked on Setter Dependency Injection. It injects a repository bean into a service bean.

## Files
* `applicationContext.xml` – Spring XML file containing bean definitions
* `BookRepository.java` – Data access repository bean class
* `BookService.java` – Business service bean class
* `LibraryManagementTest.java` – test class for loading the Spring context
* `pom.xml` – Maven file containing dependencies and build settings

## My Approach
I configured a setter method in BookService and wired the BookRepository reference using property tags in XML.

## How to Run
```bash
mvn clean test
```

## Output
Spring adds the repository into the service, allowing the service to execute repository methods .

## What I Understood
I learned how XML property wiring handles setter dependency injection.
