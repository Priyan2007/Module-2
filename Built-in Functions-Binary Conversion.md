# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

```
a = 16
print(bin(a))
```

## Output
<img width="234" height="128" alt="image" src="https://github.com/user-attachments/assets/e741d98f-9627-47d8-b9f4-d1ae5f97d4c8" />


## Result
thus the code run successfully!

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
    print(a % b)

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

result(a, b)
```

## Output
<img width="685" height="282" alt="image" src="https://github.com/user-attachments/assets/5e01bc10-2a74-4d02-bea2-54e307df4f0e" />

## Result
Thus the code run successfully!

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

f = lambda a, b: a + b

print(f(a, b))
```

## Output
<img width="598" height="255" alt="image" src="https://github.com/user-attachments/assets/ddcd3bf3-87ff-4857-a4bc-8515ef8c2401" />


## Result
Thus the code run successfully!

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
n = int(input("Enter number of rows: "))

for i in range(n):
    for j in range(n - i - 1):
        print(" ", end="")

    num = 1
    for j in range(i + 1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)
    
    print()
```

## Sample Output
<img width="373" height="275" alt="image" src="https://github.com/user-attachments/assets/db00adbb-c5cd-402b-b83e-244258d2b001" />


## Result
Thus the code run successfully!



