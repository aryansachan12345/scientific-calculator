# scientific-calculator
Project Title:
Scientific Calculator using Method Overloading in Java

Project Description:
This project is a Scientific Calculator application developed using Java that demonstrates the concept of method overloading, a core principle of Object-Oriented Programming (OOP). The calculator can perform both basic arithmetic operations and advanced scientific functions, such as trigonometric, exponential, and logarithmic calculations.

The main aim of this project is to show how method overloading allows developers to define multiple methods with the same name but different parameter lists, making the code more organized, modular, and flexible.

Key Features:
✅ Basic Operations: Addition, Subtraction, Multiplication, Division

🔁 Method Overloading: Multiple versions of methods (e.g., add(int, int), add(double, double), add(int, int, int))

📐 Scientific Functions:

Trigonometric: sin(), cos(), tan()

Power and root: pow(), sqrt()

Logarithmic: log()

⚠️ Error Handling: Robust input validation and exception handling (e.g., division by zero, invalid input)

💡 Modular Code Design: Each operation is implemented in a separate method for clarity and maintainability

Technologies Used:
Programming Language: Java

Core Concepts: Method Overloading, OOP, Exception Handling

Development Tools: Any Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse)

Example of Method Overloading:
public double add(int a, int b) {
    return a + b;
}

public double add(double a, double b) {
    return a + b;
}

public double add(int a, int b, int c) {
    return a + b + c;
}

