# Mockito Stubbing

## About the Exercise
In this exercise, I worked on Mockito mocking and stubbing. It overrides dependency behaviors for testing.

## Files
* `ExternalApi.java` – interface used as an external dependency
* `MyService.java` – service class that calls the dependency
* `MyServiceTest.java` – Unit tests utilizing mocked interfaces and stubs
* `pom.xml` – Maven file containing dependencies and build settings

## My Approach
I used Mockito to mock the ExternalApi interface and stubbed its methods using when/thenReturn syntax.

## How to Run
```bash
mvn clean test
```

## Output
The tests check the MyService component and verify its functionality with mock data.

## What I Understood
I learned how mocking database or API dependencies makes testing single components easier.
