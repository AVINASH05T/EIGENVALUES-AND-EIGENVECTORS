# EXPERIMENT: 4
# EIGENVALUES AND EIGENVECTORS
## NAME: AVINASH T
## REG NO: 212223230026
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```c
#Program to find the eigen values and eigen vectors.
#Developed by: AVINASH T
#RegisterNumber: 212223230026
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
![image](https://github.com/AVINASH05T/EIGENVALUES-AND-EIGENVECTORS/assets/151514286/71e66939-20ae-4d78-8fe8-d836ea46d032)
## Output:
![image](https://github.com/AVINASH05T/EIGENVALUES-AND-EIGENVECTORS/assets/151514286/39282c45-83bc-452f-9b42-8c4b84792473)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
