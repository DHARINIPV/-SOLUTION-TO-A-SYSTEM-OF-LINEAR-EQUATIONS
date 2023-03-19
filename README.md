# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

## Aim:
To write a python program to find a solution to a system of linear equations.

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation

### Step 2: 
Prepare the lists from each linear equations and assign in np.array()

### Step 3: 
Using the np.linalg.solve(), we can find the solutions.

### Step 4: 
End the program

## Program:
#Program to find the solution for the given linear equations.

#Developed by: Dharini PV

#RegisterNumber: 212222240024

import numpy as np

A=np.array([[1,-3],[3,1]])

B=np.array([0,10])

soln=np.linalg.solve(A,B)

print(soln)

## Output:

![Screenshot 2023-03-19 111330](https://user-images.githubusercontent.com/119400845/226156125-d3ff8140-85c6-4d05-a956-a985f8d78561.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

