# CODTECH-Task1
NAME: MARIDI SAI GAMYA
COMPANY: CODTECH IT SOLUTIONS
ID: CT12DS626
Domain: Java Programming
Duration: 10th June to 10th August
Mentor: G.Sravani
**Overview of the Project**
Project: Simple Calculator
__Objective__:
The objective of the SimpleCalculator Java program is to create a basic calculator that allows users to perform arithmetic operations (+, -, *, /) on two numbers entered via the console.The SimpleCalculator program effectively interacts with the user via console input to perform basic arithmetic calculations. It handles user input validation, error management (especially division by zero), and outputs the computed result. This program serves as a foundational example of basic control flow, input/output handling, and error handling in Java programming.
***Key Activities***:
User Input Handling:Operation Selection:
Prompts the user to choose an operation (+, -, *, /) by printing "Choose an operation (+, -, *, /): ".
Reads the user's input using scanner.next().charAt(0) to get the first character entered.
Arithmetic Operations
Switch Statement:
Uses a switch statement to determine which arithmetic operation to perform based on the operation variable:
case '+': Adds n1 and n2.
case '-': Subtracts n2 from n1.
case '*': Multiplies n1 and n2.
case '/':
Checks if n2 is not zero before dividing n1 by n2.
If n2 is zero, outputs an error message "Error: Division by zero." and sets validOperation to false.
3. Error Handling
Invalid Operation:
If the user enters an invalid operation (not +, -, *, /), prints "Error: Invalid operation." and sets validOperation to false.
__*Technologies Used*__:
 Java Programming Language:Java is a widely used programming language known for its platform independence (write once, run anywhere), object-oriented nature, and extensive standard library (java.util.Scanner in this case).
 java.util.Scanner Class: Scanner is a class in Java used for obtaining user input from the console. It allows reading various types of input, such as integers, doubles, and characters, which makes it suitable for interactive console applications like this calculator.
 
