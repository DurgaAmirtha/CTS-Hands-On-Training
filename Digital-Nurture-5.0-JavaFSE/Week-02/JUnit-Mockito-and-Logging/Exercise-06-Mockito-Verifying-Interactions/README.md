# Mockito Interaction Verification Exercise

## Objective
In this exercise, I worked on interaction checks. It checks that methods on mocked dependencies are invoked.

## Implementation
### Project Files
* `ExternalApi.java` – interface used as an external dependency
* `MyService.java` – service class that calls the dependency
* `MyServiceTest.java` – Unit tests utilizing mocked interfaces and stubs
* `pom.xml` – Maven file containing dependencies and build settings

### Implementation Details
I used Mockito's verify method to verify that dependency interactions are executed.

## How to Run
```bash
mvn clean test
```

## Expected Output
The test confirms that external calls were triggered during execution.

### Key Takeaways
I learned that verifying interactions is key when testing void methods or actions with side effects.
