# Mockito Interaction Verification

## About the Exercise
In this exercise, I worked on interaction checks. It checks that methods on mocked dependencies are invoked.

## Files
* `ExternalApi.java` – interface used as an external dependency
* `MyService.java` – service class that calls the dependency
* `MyServiceTest.java` – Unit tests utilizing mocked interfaces and stubs
* `pom.xml` – Maven file containing dependencies and build settings

## My Approach
I used Mockito's verify method to verify that dependency interactions are executed.

## How to Run
```bash
mvn clean test
```

## Output
The test confirms that external calls were triggered during execution.

## What I Understood
I learned that verifying interactions is key when testing void methods or actions with side effects.
