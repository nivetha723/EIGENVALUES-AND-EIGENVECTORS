# EIGENVALUES-AND-EIGENVECTORS
# Name: Nivetha N
# Reg.No:212225040290
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
~~~
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[-2, 2, -3],
              [2, 1, -6],
              [-1, -2, 0]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
~~~


## Output:
<img width="1305" height="776" alt="Screenshot 2026-04-28 214447" src="https://github.com/user-attachments/assets/e3b6f150-1614-4877-9ac9-8b7810fb4deb" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
