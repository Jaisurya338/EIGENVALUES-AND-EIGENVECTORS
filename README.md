# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Ramesh Jaisurya
#RegisterNumber: 25005800
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Define the matrix
matrix = np.array([[2, 2],
                   [1,3]])

# Find eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(matrix)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

```


## Output:
<img width="1212" height="898" alt="image" src="https://github.com/user-attachments/assets/d078f36d-8427-471e-aa77-ff450ba45808" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
