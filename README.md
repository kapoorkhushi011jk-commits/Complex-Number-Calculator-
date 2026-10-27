# Complex Number Calculator

## 📌 Overview
A C++ console application that performs arithmetic operations (addition and subtraction) on complex numbers using **Object-Oriented Programming** principles, specifically **operator overloading**.

---

## 🎯 Objective
Develop a calculator to perform arithmetic operations on complex numbers by overloading the `+`, `-`, and `<<` operators within a `Complex` class.

---

## ✅ Functional Requirements

| # | Requirement | Status |
|---|-------------|--------|
| 1 | Create a `Complex` class to store real and imaginary parts | ✅ |
| 2 | Overload the `+` operator to add two complex numbers | ✅ |
| 3 | Overload the `-` operator to subtract two complex numbers | ✅ |
| 4 | Overload the `<<` operator to display a complex number | ✅ |
| 5 | Accept two complex numbers and display addition & subtraction results | ✅ |

---

## 🧩 OOP Concepts Used

- **Classes & Objects** — `Complex` class with multiple object instances.
- **Encapsulation** — Private data members (`real`, `imaginary`) with public getter methods.
- **Constructors** — Default and parameterized constructors.
- **Operator Overloading** — `operator+`, `operator-` (member), `operator<<` (friend).

---

## 🛠️ Prerequisites

- **C++ Compiler** — GCC (g++) 7.0+ or any C++11-compliant compiler.
- **Operating System** — Windows / macOS / Linux.
- **IDE (Optional)** — VS Code, Code::Blocks, Dev-C++, CLion, etc.

---

## 🚀 How to Compile & Run

### Using the Command Line (GCC)

```bash
# Step 1: Compile
g++ -o complex_calculator main.cpp

# Step 2: Run
./complex_calculator        # Linux / macOS
complex_calculator.exe      # Windows
