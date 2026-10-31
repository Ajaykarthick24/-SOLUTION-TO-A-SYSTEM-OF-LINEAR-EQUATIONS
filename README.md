<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/ef6c2557-7041-4908-bd5d-2e25627b6f2e" /># -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
'''
#Program to find the solution for the given linear equations.
#Developed by: Ajay Karthick M
#RegisterNumber: 212225040014
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array([[1, -3], [3, 1]])
B = np.array([0, 10])

C = np.linalg.solve(A, B)

print(C)

'''
## Output:

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/b85d05c6-0109-4c18-8abc-c14153474393" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

