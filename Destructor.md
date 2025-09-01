# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program

class Demo:
    
    def _init_(self):
    
        self.status = "Alive"
   
    def _del_(self):
        
        print("The object no longer exists")

obj = Demo()

print(obj.status)

del obj

## 🧪 Output

![WhatsApp Image 2025-09-01 at 20 22 54_e8d92f2d](https://github.com/user-attachments/assets/f486c29d-204c-47af-8495-4c635006a5f3)

## Result
Thus,the  project demonstrates how to implement a **destructor** in Python using a simple class is verified.


