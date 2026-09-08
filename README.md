# Creating a program to find the hypotenuse of a right triangle using the math library!!
## description
### - How does this program run? This program asks you for the length of side and side b
### - this program uses the formula : c = sqrt(a^2 + b^2)
### ! the user must input valid numerical numbers to make sure the code runs smoothly
### *The inputs needed are:
#### - length of side a
#### - length of side b
### - What is an example of an output to this program?
### - 🌮 THe hypotenuse of your right triangle is is [c] (c is the hypotenuse, it represents the answer)
#### - [c] comes from the answer formed using the formula and inputs
#### Author : Gileana Hannah G. saguil
#### - Section : 8 - sampaguita



# Author - GILEANA HANNAH G. SAGUIL
# Activity 3 ARAL mode August 19, 2026

print("HYPOTHENUS CALULATOR !!!  🥳😇")

import math

a = float(input("Enter the length of side a: "))
b = float(input("Enter the length of side b: "))
a2 = pow(a,2)
b2 = pow(b,2)
c2 = a2 + b2
c = math.sqrt(c2)
print(f"The hypotenuse is: {c:.2f}")
