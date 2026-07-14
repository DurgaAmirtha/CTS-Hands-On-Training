# AAA Pattern and Fixtures

## About the Exercise
This exercise implements the Arrange-Act-Assert pattern and handles JUnit setup/teardown fixtures.

## Files
* `Calculator.java` – Basic arithmetic calculation module
* `CalculatorTest.java` – JUnit test checking calculator math actions using AAA pattern
* `pom.xml` – Maven file containing dependencies and build settings

## My Approach
I set up a calculator instance inside a @Before annotated method and structured the tests in three distinct steps (Arrange, Act, Assert).

## How to Run
```bash
mvn clean test
```

## Output
The unit tests verify addition, subtraction, multiplication, and division on the calculator instance.

## What I Understood
I learned how setup and teardown fixtures ensure each test runs on a clean state.
