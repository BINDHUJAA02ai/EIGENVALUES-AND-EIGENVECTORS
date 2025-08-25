# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import NumPy library, np.linalg is its linear algebra module, which provides the eig() function to compute eigenvalues and eigenvectors
### Step 2: Create a square matrix, Eigenvalues and eigenvectors can only be found for square matrices (same number of rows and columns).
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:Print the result, This line displays the eigenvalues and eigenvectors. 
## Program:
```
#Developed by: Bindhujaa S
#RegisterNumber:212224230038
import numpy as np
A = np.array([[2, 2],
              [1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```

## Output:
<img width="1267" height="901" alt="image" src="https://github.com/user-attachments/assets/83a553da-7a06-4837-8c05-15609310302d" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
