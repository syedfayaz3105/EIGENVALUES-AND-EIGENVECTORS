# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy moudle to use the builtin function for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array().
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Farhana H
#RegisterNumber: 23012987
import numpy as np
a=[[2,2],[1,3]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![image](https://github.com/syedfayaz3105/EIGENVALUES-AND-EIGENVECTORS/assets/147144126/780b39b2-e5ef-4f44-a593-5b3c7f3de3e6)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
