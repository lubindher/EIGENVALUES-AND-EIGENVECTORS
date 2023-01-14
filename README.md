# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the eigenvalues and eigenvectors and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Lubindher
#RegisterNumber:22009019
import numpy as np
a=np.array([[2,2],[1,3]])
val,vec=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(val,vec))

## Output:
![output](./Screenshot%202023-01-14%20154157.jpg)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
