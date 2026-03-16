# Even and Odd Number Checker

This program is a simple Java Swing GUI application that checks whether a number entered by the user is positive, negative, or zero and also determines whether the number is even or odd.

## How it Works

1. The user enters a number in the input text field.
2. The program reads the value using Integer.parseInt().
3. It first checks whether the number is zero.
4. If the number is not zero, the program checks whether it is positive or negative.
5. Then it uses the modulus operator (%) to determine whether the number is even or odd.
6. The result is displayed using a JOptionPane message dialog.

## Features

- Accepts integer input from the user
- Identifies if the number is:
  - Positive and Even
  - Positive and Odd
  - Negative and Even
  - Negative and Odd
  - Zero (special case)
- Displays results using a pop-up message dialog

## Technologies Used

- Java
- Java Swing
- NetBeans IDE

## Purpose

This program was created as a practice exercise to understand:
- Conditional statements (if-else)
- Modulus operator
- Event handling in Java Swing
- User input handling in GUI applications
