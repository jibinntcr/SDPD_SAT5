# Calculator App

## Description
A simple calculator application built using **Kotlin**. This calculator supports basic arithmetic operations and is designed to be a console-based application.

## Features
- Addition   
- Subtraction  
- Multiplication 
- Division (`/`)
- Modular operation (`%`)
- Exit option to terminate the program

## Prerequisites
- Install **Kotlin**: [https://kotlinlang.org/docs/getting-started.html](https://kotlinlang.org/docs/getting-started.html)
- Install **Java JDK** (Version 8 or later): [https://www.oracle.com/java/technologies/javase-jdk11-downloads.html](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

## How to Run the Application

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/calculator-app.git
   cd calculator-app
   ```

2. **Compile the Kotlin File**
   ```sh
   kotlinc Calculator.kt -include-runtime -d Calculator.jar
   ```

3. **Run the Application**
   ```sh
   java -jar Calculator.jar
   ```

## Example Usage
```txt
Enter first number: 10
Enter operation (+, -, *, /, %): *
Enter second number: 5
Result: 50
```

## File Structure
```
calculator-app/
│── Calculator.kt  # Main Kotlin source code
│── README.md      # Project documentation
```

