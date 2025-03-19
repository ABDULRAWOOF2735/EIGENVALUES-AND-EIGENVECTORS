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
### Step 4: End the Program

## Program:
    import numpy as np
    matrix = np.array([[2, 2], [1, 3]])
    eigenvalues, eigenvectors = np.linalg.eig(matrix)
    print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
## Output:
![image](https://github.com/user-attachments/assets/c6fb97c1-0508-4657-b6e8-abbe67ed75fc)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
