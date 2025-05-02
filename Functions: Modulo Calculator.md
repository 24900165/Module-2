# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    return a % b

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("The result of the modulo operation is:", result(a, b))
```

## Output
```
Enter first number: 10
Enter second number: 3
The result of the modulo operation is: 1
```

## Result

The program successfully defines a function that computes the modulo of two numbers and returns the result.
