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

def init(self):

self.status = "Alive"
def del(self):

print("The object no longer exists")
obj = Demo()

print(obj.status)

del obj

## 🧪 Output

<img width="486" height="144" alt="488732188-cf13a634-ac11-4813-909c-b363f67293a4" src="https://github.com/user-attachments/assets/7c8bafa4-7895-4c4a-a5f3-d09b71ec49df" />

## Result
Thus, This project demonstrates how to implement a destructor in Python using a simple class.

