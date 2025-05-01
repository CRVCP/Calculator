# Simple Java Calculator

This project is a basic command-line calculator written in Java, created to satisfy a rubric very simply. It performs simple arithmetic operations—addition, subtraction, multiplication, and division—on two user-provided numbers.

## Features

- Accepts user input for two numeric values
- Supports the following operations: `+`, `-`, `*`, `/`
- Handles invalid inputs gracefully, including:
  - Non-numeric input
  - Invalid operators
  - Division by zero

## How to Run

1. Compile the program:
   ```bash
   javac Calculator.java
 
2. Run the compiled program Calculator.java


## Example
Enter the first number: 10  
Enter the second number: 5  
Enter an operator (+, -, *, /): *  
Result: 50.0  


## Notes
Written in Java 17+ (uses switch expression with yield)
All input is validated to prevent runtime exceptions
Scanner is properly closed as a best practice
