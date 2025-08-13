# Task-1-and-Task-2
def factorial(n):

    if n == 0 or n == 1:
        return 1
    else:
        return n * (factorial(n-1))

num = int(input("Enter a number: "))
print("Factorial is:",factorial(num))

import math

number = float(input("Enter a number: "))

print("Square root:",math.sqrt(number))

print("Natural logarithm:",math.log(number))

print("Sine (radians):",math.sin(number))
