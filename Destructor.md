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
class Demo:
    def __init__(self, value):
        self.value = value 
    def display(self):
        print(f"The value of this instance is: {self.value}")


demo_instance = Demo(10)

print(demo_instance.value)  

demo_instance.display()   

## 🧪 Output
<img width="1100" height="394" alt="image" src="https://github.com/user-attachments/assets/b77f6ab1-5155-407b-aa2d-0d294b8cd676" />
<img width="1231" height="289" alt="{1463F396-B828-43EF-868D-8DF6CD1A09AE}" src="https://github.com/user-attachments/assets/b63801ac-b44b-4741-8dc3-cf255bf4c523" />


## Result
hence the code is written and executed

