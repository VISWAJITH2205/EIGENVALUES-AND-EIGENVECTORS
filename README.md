# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculations.

### Step 2:
Prepare the lists from each equations and assign in np.array()

#### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
END OF PROGRAM

## Program:
```
#Program to find the eigen values and eigen vectors.

import numpy as np
A = np.array([[2, 2],
              [1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

#Developed by: VISWAJITH LALITHRAM R.V
#RegisterNumber: 212224240187
```
## Output:

<img width="1173" height="597" alt="Screenshot 2025-08-25 211810" src="https://github.com/user-attachments/assets/998d8646-21ef-4729-8f40-48a039d519c4" />



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
