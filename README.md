# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : 

Import numpy package.

### Step 2: 

Get the input matrix.

### Step 3:

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

Print the result.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:DINESH KUMAR R 
#RegisterNumber:212222110010
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)
```

## Output:

![1 d maths](https://user-images.githubusercontent.com/119477784/231480201-4604ebba-6956-4cad-87f6-2250e39f86ef.png)

## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
