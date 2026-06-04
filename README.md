# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import the NumPy library.
### Step 2:  Create a matrix using np.array().
### Step 3:  Using the np.linalg.inv() function, find the inverse of the given matrix.
### Step 4:  Display the inverse of the matrix.

## Program:
```
name:avanesh.r
reg no:212225240018
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
result=np.linalg.inv(A)
print(result)
```
## Output:
<img width="795" height="845" alt="Screenshot 2026-05-05 184308" src="https://github.com/user-attachments/assets/2627e73d-90c0-4419-8e63-cc011cf99487" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

