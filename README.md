# my-first-calculator
# My First Calculator in Python

This is my first Python project, created using my phone (Pydroid 3, since I don't have a laptop yet). The calculator allows you to perform basic arithmetic operations: addition, subtraction, multiplication, and division.

## What I learned:
- How to use input() to get user input.
- Basic arithmetic operations in Python.
- Conditional statements (`if`, `elif`, `else`) to choose the correct operation.
- Basic error handling to check for invalid operations.

### How to use:
1. Enter the first number.
2. Enter the second number.
3. Choose the operation you want to perform (`+`, `-`, `*`, `/`).
4. The result will be printed on the screen.

#### Code:
```python
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter the operation (+, -, *, /): ")

if operation == "+":
    print("Result:", num1 + num2)
elif operation == "-":
    print("Result:", num1 - num2)
elif operation == "*":
    print("Result:", num1 * num2)
elif operation == "/":
    print("Result:", num1 / num2)
else:
    print("Invalid operation")
