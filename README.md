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
import os

os.environ["OPENBLAS_NUM_THREADS" ]="1"

import numpy as np

A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])

B=np.array([-9,4,-1])

C=np.linalg.solve(A,B)

print(C)


## Output:<img width="797" height="640" alt="{FF9BE9D4-BA23-44A8-ADE7-5DE1F5D2FEAA}" src="https://github.com/user-attachments/assets/d0168f3b-88e3-402c-a398-78084d9a8200" />
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

