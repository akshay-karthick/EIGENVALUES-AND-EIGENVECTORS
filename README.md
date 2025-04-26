# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:  
Import the necessary library, `numpy`, for matrix operations.  

### Step 2:  
Define the given matrix using the `numpy.array()` method.  

### Step 3:  
Using the `np.linalg.eig()`, we get two results (first is eigenvalue and second is eigenvector) of the given matrix.  

### Step 4:  
Display the eigenvalues and eigenvectors using the `print()` function.  

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Akshay Karthick ASR
#RegisterNumber: 212224230015
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```
## Output:
![image](https://github.com/user-attachments/assets/ce6ff46d-8494-472c-a5e9-206b682336ec)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
