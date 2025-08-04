# Simple Java Calculator

## Overview
This is a command-line Java calculator that supports addition, subtraction, multiplication, and division. The user is prompted to choose an operation and input two numbers; the result is displayed. Entering `$` exits the program.

## What Was Done
- **Reviewed original code** for functional and robustness issues.
- **Improved input validation**: ensured only valid operations are accepted and handled non-numeric input gracefully.
- **Fixed division-by-zero logic** so that it does not attempt to print an invalid result.
- **Refactored control flow** using a `switch` for clarity.
- **Separated concerns**: clear messaging and looping logic.
- **Added example usage** in comments.
- **(Optional)** Included a simple JUnit test class template for future automated testing.

## Files
- `Calculator.java`: Main interactive calculator program.
- `CalculatorTest.java`: (Optional) JUnit test skeleton to test arithmetic operations.

## How to Compile and Run
cmd--
# Compile 
javac Calculator.java

# Run
java Calculator
