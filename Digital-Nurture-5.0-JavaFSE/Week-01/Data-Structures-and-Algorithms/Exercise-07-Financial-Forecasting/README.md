# Financial Forecasting Exercise

## Objective
In this exercise, I calculated the future value of an investment using a recursive method.

## Implementation
### Project Files
* `Forecasting.java` – Future value computation class
* `ForecastingTest.java` – JUnit tests verifying growth output predictions
* `pom.xml` – Maven file containing dependencies and build settings

### Implementation Details
The method applies the growth rate for each remaining year until it reaches the base case.

## How to Run
```bash
mvn clean test
```

## Expected Output
The program finds the forecasted value recursively and compares it with an iterative loop calculation.

### Key Takeaways
I learned how recursion works using a base condition and repeated method calls.
