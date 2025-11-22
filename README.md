# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Form a matrix using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigen vectors and eigen values. 
### Step 5: End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: BALAJI S
#RegisterNumber: 25012884
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/fcc84ee9-05ea-4e89-80c3-141e02a0bb4f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
