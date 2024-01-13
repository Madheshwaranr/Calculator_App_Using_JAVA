# Java Swing Calculator

## Class and Package Structure:

- The code is organized into a package named `calculator`.
- The main class is `CalculatorUI`, which extends `javax.swing.JFrame` for creating a GUI window.

## Initialization and Variables:

- The `CalculatorUI` class initializes a set of variables, including `CalTotal` (a string to store the entered numbers and operators), `num1` and `num2` (integers to store operand values), `option` (a string to store the selected operation), and `result` (an integer to store the calculation result).

## GUI Components:

- The GUI includes a JTextArea (`txtTOTAL`) to display the input and output.
- Buttons (JButton) labeled with digits (0-9), arithmetic operators (+, -, *, /), and a few control buttons (CLEAR, =) are provided.

## Button Action Listeners:

- Each digit button (0-9) has an associated action listener that appends the corresponding digit to the `txtTOTAL` JTextArea when clicked.
- The arithmetic operation buttons (+, -, *, /) store the current value in `num1` and the selected operation in `option`. The `txtTOTAL` is then cleared for the next input.
- The CLEAR button resets all variables and clears the `txtTOTAL` JTextArea.
- The = button performs the calculation based on the selected operation and displays the result in the `txtTOTAL` JTextArea.

## Main Method:

- The `main` method sets the look and feel of the UI, creating an instance of `CalculatorUI` and making it visible.

## Usage:

- Run the program, and a calculator window will appear.
- Click the digit buttons to input numbers.
- Use the arithmetic operation buttons to perform calculations.
- CLEAR button resets the calculator.
- = button calculates and displays the result.

## Enhancements:

- You can further improve the calculator by adding features like decimal support, handling edge cases, and improving the user interface.

## How to Run:

1. Make sure you have Java installed on your machine.
2. Clone the repository.
3. Compile and run the `CalculatorUI` class.

```bash
javac calculator/CalculatorUI.java
java calculator.CalculatorUI


📫 **Contact:**

LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/madheshwaran-r-b6a454209)

Email: madheshravi2001@gmail.com

Let's connect and create amazing things!

[My website portfolio](https://madheshwaranr.github.io/My_Portfolio/)

