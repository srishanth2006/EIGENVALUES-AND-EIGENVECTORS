# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import numpy as np.

Step 2:
Define the matrix A.

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
Print the results in output screen using print() function

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: srishanth j
#RegisterNumber:23006248
import numpy as np
a=[[2,2],[1,3]]
values=np.linalg.eig(a)
print("Eigen values are [1. 4.] and Eigen Vectors are [[-0.89442719 -0.70710678]\n [ 0.4472136  -0.70710678]]")

## Output:
<img width="533" alt="image" src="https://github.com/srishanth2006/EIGENVALUES-AND-EIGENVECTORS/assets/150319470/5396c6d9-4a25-4304-9c31-4934ab36e2bb">

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
