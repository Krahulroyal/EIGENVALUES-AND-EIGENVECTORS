# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
A = [[2,2],[1,3]]
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
values,vectors = np.linalg.eig(A)
### Step 4: 
print("Eigen values are",values ,"and Eigen Vectors are",vectors)
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: K.Rahul Royal
#RegisterNumber: 24001378
## Output:
![alt text](<Screenshot 2024-12-16 110132.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
