# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(), we can find the Eigenvalues and Eigen Vectors.
### Step 4: 
End the program

## Program:
```
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1326" height="873" alt="Screenshot 2026-02-14 172732" src="https://github.com/user-attachments/assets/f496c6f2-9ad3-4a29-8eda-747a3a51d6da" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
