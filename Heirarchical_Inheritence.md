# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
class details:

    def __init__(self,id,name,gender):
        self.id=id
        self.name=name
        self.gender=gender
class employee(details):

    def __init__(self,id,name,gender,comp,dep):
        super().__init__(id,name,gender)
        self.comp=comp
        self.dep=dep
    def display(self):
        print("Employee Object")
        print("Id: ",self.id)
        print("Name: ",self.name)
        print("Gender: ",self.gender)
        print("Company: ",self.comp)
        print("Department: ",self.dep)
class patient(details):

    def __init__(self,id,name,gender,hosp,dep):
        super().__init__(id,name,gender)
        self.hosp=hosp
        self.dep=dep
    def display(self):
        print("\nPatient Object")
        print("Id: ",self.id)
        print("Name: ",self.name)
        print("Gender: ",self.gender)
        print("Hospital: ",self.hosp)
        print("Department: ",self.dep)
        
emp=employee(int(input()),input(),input(),input(),input())

emp.display()

pat=patient(int(input()),input(),input(),input(),input())

pat.display()


## Sample Output

<img width="671" height="459" alt="Screenshot 2025-09-01 184112" src="https://github.com/user-attachments/assets/47daeafe-ea96-4501-b1a8-69250e9f5d8f" />

result
Thus, a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details is verified.

