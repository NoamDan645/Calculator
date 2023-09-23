# Calculator Project

## Description

This project is a calculator implemented in the C programming language. The calculator is built using the Shunting Yard algorithm, which is a widely-used algorithm for parsing mathematical expressions.

## Shunting Yard Algorithm

The Shunting Yard algorithm is an efficient method for converting infix expressions (the usual human-readable format) into postfix notation, also known as Reverse Polish Notation (RPN). This allows for the easy evaluation of mathematical expressions using a stack-based approach.

## How the Calculator Works

1. **Input**: The calculator accepts mathematical expressions as input in the standard infix notation. For example, you can enter expressions like `2 + 3 * (4 - 1)`.

2. **Parsing**: The input expression is first parsed and converted into postfix notation using the Shunting Yard algorithm.

3. **Evaluation**: After converting the expression into postfix notation, the calculator evaluates the expression by iterating through each token (number or operator) and using a stack to perform the calculations.

4. **Output**: The calculator then provides the result of the expression.

## Usage

To use the calculator, follow these steps:

1. Clone or download this repository.

2. Compile the C code using a C compiler. For example:
   ```sh
   gcc calculator.c -o calculator
