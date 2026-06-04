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
```
import numpy as np  

a=np.array(eval(input())) 

b=np.array(eval(input())) 

print("Printing Original array") 

print(a) 

print("Array after deleting column 2 on axis 1") 

c=np.delete(a,1,axis=1)  

print(c) 

print("Array after inserting column 2 on axis 1") 

print(np.insert(c,1,b,axis=1))
```
## 🧪 Output

<img width="941" height="272" alt="image" src="https://github.com/user-attachments/assets/876ad118-6083-4b3e-81aa-14a9e6d9f314" />


## Result
Thus the python program for replacing column in numpy has been implemented and executed successfully.


