# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
f = lambda a, b: a + b

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("The sum is:", f(a, b))
```
## Output
```
Enter first number: 5
Enter second number: 7
The sum is: 12
```
## Result

The program successfully defines a lambda function that computes the sum of two numbers and prints the result.
