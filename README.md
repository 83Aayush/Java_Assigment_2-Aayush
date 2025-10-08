# Calculator Application Using Method Overloading

## 📘 About the Project
This is a simple Java console-based calculator made to demonstrate the concept of **method overloading**.  
It performs basic arithmetic operations like addition, subtraction, multiplication, and division.  
Each operation is handled using overloaded methods that work with different data types and numbers of inputs.

---

## 🎯 Objective
The main goal of this project is to understand how **method overloading** works in Java and how it can be used to perform similar operations on different data types.  
It also helps in learning how to take user input, handle exceptions, and build a simple menu-driven application.

---

## ⚙️ Features
- Add, Subtract, Multiply, and Divide operations  
- Overloaded methods for different parameter types and counts  
- Handles both integers and doubles  
- Gracefully manages divide-by-zero errors  
- Simple and clear text-based user interface  

---

## 🧩 Classes and Methods
### 1. `Calculator` Class
Contains all the logic for arithmetic operations:
- `add(int a, int b)`
- `add(double a, double b)`
- `add(int a, int b, int c)`
- `subtract(int a, int b)`
- `multiply(double a, double b)`
- `divide(int a, int b)`

### 2. `CalculatorApp` Class
Handles user input and displays the menu:
- `performAddition()`
- `performSubtraction()`
- `performMultiplication()`
- `performDivision()`
- `mainMenu()`

---


---

## 🚀 How to Run the Program
1. Save the file as `CalculatorApp.java`
2. Open Command Prompt or Terminal in the folder where the file is saved
3. Compile the code:
   ```bash
   javac CalculatorApp.java

