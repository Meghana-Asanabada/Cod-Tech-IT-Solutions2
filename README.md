Basic Calculator Documentation
Overview
BasicCalculator is a simple console-based calculator program implemented in Java. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

Features
User-Friendly Interface: The program presents a menu of available operations and guides the user through the calculation process.
Error Handling: The program handles division by zero gracefully and prompts the user to enter a non-zero divisor.
Continuous Operation: The calculator runs in a loop, allowing users to perform multiple calculations without restarting the program.
Clean Code: The program is well-structured and utilizes methods for each arithmetic operation, enhancing readability and maintainability.
Classes
BasicCalculator
Main class: Contains the main method to start the calculator.
Methods:
main(String[] args): Entry point of the calculator program.
add(double num1, double num2): Adds two numbers and returns the result.
subtract(double num1, double num2): Subtracts the second number from the first and returns the result.
multiply(double num1, double num2): Multiplies two numbers and returns the result.
divide(double num1, double num2): Divides the first number by the second and returns the result.
Usage
Run the BasicCalculator class.
Follow the on-screen prompts to select the desired arithmetic operation and enter the numbers to perform the calculation.
Repeat steps 2 as needed for additional calculations.
Choose the "Exit" option to end the calculator program.
Examples
Addition: Enter two numbers to calculate their sum.
Subtraction: Enter two numbers to calculate their difference.
Multiplication: Enter two numbers to calculate their product.
Division: Enter two numbers to calculate their quotient. If the divisor is zero, the program displays an error message.
Dependencies
java.util.Scanner: Used for user input.
Notes
The calculator program only performs basic arithmetic operations and does not support advanced mathematical functions.
Users can exit the program by selecting the "Exit" option from the menu.
