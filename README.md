# Java ArithmeticException: Integer Division by Zero

This repository demonstrates a common, yet easily avoidable, error in Java: the `ArithmeticException` that occurs when dividing an integer by zero.

## The Bug
The `bug.java` file contains code that attempts to divide an integer by zero, leading to an `ArithmeticException` at runtime. This is a runtime exception, meaning it doesn't prevent compilation but will crash the program when executed.

## The Solution
The `bugSolution.java` file provides a corrected version of the code. It includes a check to avoid division by zero, either by explicitly handling the case of a zero divisor or using a conditional statement to avoid the division entirely.

## How to Run
1.  Clone the repository.
2.  Compile the Java code using a Java compiler (like `javac`):
    ```bash
    javac bug.java
    javac bugSolution.java
    ```
3.  Run the compiled code:
    ```bash
    java bug
    java bugSolution
    ```
Observe the difference in output and behavior between the buggy and corrected versions.