# Singleton Pattern Exercise

## Objective
In this exercise, I worked on the Singleton design pattern. The logger class allows only one object to be created and returns the same object whenever it is requested.

## Implementation
### Project Files
* `Logger.java` – Logger class implementing Singleton pattern
* `LoggerTest.java` – Unit test verifying the Singleton implementation
* `pom.xml` – Maven file containing dependencies and build settings

### Implementation Details
The constructor is private so that the class cannot be instantiated from outside. A static method returns the single logger instance.

## How to Run
```bash
mvn clean test
```

## Expected Output
The test creates two logger instances and asserts that both references point to the exact same object in memory.

### Key Takeaways
I learned how a private constructor and a static instance can be used to control object creation.
