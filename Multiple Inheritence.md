# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
a=int(input())

b=int(input())

div = a/b

sub=a-b

mul=a*b

print(div)

print(sub)

print(mul)

## Output Example

<img width="568" height="216" alt="Screenshot 2025-09-01 185237" src="https://github.com/user-attachments/assets/d7512233-4118-43b6-8933-dff91089a090" />

## Result
Thus, a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance** is verified.
