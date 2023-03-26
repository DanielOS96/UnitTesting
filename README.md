# Unity Unit Testing Example

This repository contains a simple Unity project that demonstrates how to create and run unit tests using the Unity Test Runner. The project includes a basic calculator class and a set of unit tests to verify the correct behavior of the calculator's operations.

## Calculator

The `Calculator` class is a basic calculator implementation that supports the following operations:

- Add
- Subtract
- Multiply
- Divide

These operations are demonstrated in the `Calculator.cs` script.

## Unit Tests

The `CalculatorTests` class contains a set of unit tests that verify the correct behavior of the calculator's operations. These tests are implemented using the NUnit testing framework and can be executed within Unity using the Unity Test Runner.

The `CalculatorTests.cs` script contains the following test cases:

- Add_AddsTwoNumbers_ReturnsCorrectResult
- Subtract_SubtractsTwoNumbers_ReturnsCorrectResult
- Multiply_MultipliesTwoNumbers_ReturnsCorrectResult
- Divide_DividesTwoNumbers_ReturnsCorrectResult
- Divide_DividesByZero_ThrowsDivideByZeroException
- Add_AddsTwoNumbers_FailsIntentionally (This test is designed to fail intentionally to demonstrate a failing test case.)

## Running Tests

To run the tests, follow these steps:

1. Open the project in Unity.
2. Go to `Window` -> `General` -> `Test Runner`.
3. In the Test Runner window, click "Run All" under the "EditMode" tests.
4. Observe the test results. All tests should pass except for the intentionally failing test case `Add_AddsTwoNumbers_FailsIntentionally`, which will be marked red.
