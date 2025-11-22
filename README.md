# EIGENVALUES-AND-EIGENVECTORS
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
```
#Program to find the eigen values and eigen vectors.
#Developed by:S.Ranjani 
#RegisterNumber: 25017557
import numpy as np
a=np.array ([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1282" height="265" alt="Screenshot 2025-11-22 143229" src="https://github.com/user-attachments/assets/72de7133-2e45-4ab1-ae69-e8c428a27bc3" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
