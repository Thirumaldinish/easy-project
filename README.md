
# 🧮 Simple Python Calculator

A basic Python console application that performs fundamental arithmetic operations: **addition, subtraction, multiplication, and division**.

---

## 📋 Features

* Easy-to-use console interface
* Supports:

  * Addition
  * Subtraction
  * Multiplication
  * Division (with division-by-zero handling)
* Input validation included

---

## 🚀 Getting Started

### ✅ Prerequisites

* Python 3.x installed on your system
  You can check by running:

  ```bash
  python --version
  ```

---

### 📦 How to Run

1. Clone or download this repository.

2. Open a terminal or command prompt.

3. Run the script:

   ```bash
   python calculator.py
   ```

4. Follow the on-screen instructions to perform calculations.

---

## 💡 Example

```text
Simple Calculator
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice (1/2/3/4): 3
Enter first number: 10
Enter second number: 5
Result: 50.0
```

---

## 🛠️ Code Overview

```python
def add(x, y): return x + y
def subtract(x, y): return x - y
def multiply(x, y): return x * y
def divide(x, y): return x / y if y != 0 else "Error"
```

---

## 📄 License

This project is open-source and free to use for educational and personal projects.

---
