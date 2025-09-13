TASK 1
# 🧮 Simple Calculator in Python

This is a basic Python program that performs simple arithmetic operations: **addition, subtraction, multiplication, and division** on two numbers entered by the user.

## 📌 Features
- Takes two integer inputs from the user.  
- Performs:
  - Addition  
  - Subtraction  
  - Multiplication  
  - Division  
- Displays the results in a clear format.  

## 📝 Code
```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

sum = num1 + num2
difference = num1 - num2
product = num1 * num2
quotient = num1 / num2

p = print("Addition =", sum)
print("Subtraction =", difference)
print("Product =", product)
print("Division =", quotient)
