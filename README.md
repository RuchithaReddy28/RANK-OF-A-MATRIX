# RANK-OF-A-MATRIX

## Aim:
To write a python program to find the rank of a matrix

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists for each linear equations and assign array in np.array().

### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
Using the np.linagl.matrix_rank(A),we can find the solutions.

### Step 4: 
End the program.

## Program:.#Program to find the rank of a matrix.
#Developed by:A.Ruchitha Reddy 

#RegisterNumber:21005032

import numpy as np

A=np.array([[1, 2, 3,],[3, 6, 9]])

rk=np.linalg.matrix_rank(A)

print(rk)

## Output:
![output](https://github.com/RuchithaReddy28/RANK-OF-A-MATRIX/blob/main/Screenshot%20(12).png?raw=true)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

