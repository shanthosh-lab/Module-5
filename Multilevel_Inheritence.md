# Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

## 🎯 Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

## 🧠 Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program

class Person:
    def __init__(self, name):
        self.name = name

class Age(Person):
    def __init__(self, name, age):
        super().__init__(name)
        self.age = age

class ID(Age):
    def __init__(self, name, age, place):
        super().__init__(name, age)
        self.place = place

    def display(self):
        print(self.name, self.age, self.place)

name = input()
age = input()
place = input()

person = ID(name, age, place)

person.display()

## Sample Output

  <img width="716" height="227" alt="Screenshot 2025-09-01 184753" src="https://github.com/user-attachments/assets/1d828770-faa6-4a28-9315-acb1bdd0696d" />
## Result

Thus, a Python program that uses multilevel inheritance to get and display a person’s name, age, and location is verified.

