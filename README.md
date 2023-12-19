Description:

This is a simple quadratic equation calculator written in Python. 
It takes the coefficients of a quadratic equation (ax² + bx + c) as input and calculates the roots using the quadratic formula. 
The program handles real and complex roots.

Requirements:
Python 3.x

Files:
quadratic_calculator.py: Main Python script containing the quadratic equation calculator.

Functions:
main(): The main function that handles user input and calls the Quad_solver function.
Quad_solver(a, b, c): Function to calculate the roots of the quadratic equation.

Notes:
The program checks for valid input and ensures that the coefficient 'a' is not zero to prevent division by zero.
The determinant is calculated to determine the nature of the roots (real and distinct, real and equal, or imaginary).
