# SLF4J and Logback Logging

## About the Exercise
In this exercise, I worked on application logging. It configures Logback levels to filter messages.

## Files
* `logback.xml` – Logback configuration defining appenders and logs hierarchy
* `LoggingExample.java` – Standard logger output operations
* `LoggingExampleTest.java` – test class for checking log output
* `pom.xml` – Maven file containing dependencies and build settings

## My Approach
I added SLF4J logger calls inside the class and created a logback.xml file to specify formats and level configurations.

## How to Run
```bash
mvn clean test
```

## Output
The test output shows logs to the console showing INFO, WARN, and ERROR messages with custom formats.

## What I Understood
I learned how Logback formats and levels filter log outputs.
