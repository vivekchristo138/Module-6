# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self,length,width):
        self.length=length
        self.width=width
    def display(self):
        print(self.length)
        print(self.width)
r=Rectangle(5,3)
r.display()
```
## Output
<img width="752" height="206" alt="viv2" src="https://github.com/user-attachments/assets/5998281a-0ffd-4da8-8075-522fd6db257f" />

## Result

Thus, the Python program demonstrating Encapsulation was successfully executed using a class with private member variables.

