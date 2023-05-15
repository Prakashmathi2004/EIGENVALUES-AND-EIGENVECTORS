# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy matrix
### Step 2: 
get the import matrix
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.find the eigen value
### Step 4: 
print the result
## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: M.PRAKASH
#RegisterNumber:212222100035
import numpy as np
a=np.array([[4,2],[2,4]])
b,c=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c,)
~~~
## Output:
<img width="652" alt="image" src="https://user-images.githubusercontent.com/118350045/229300841-af4f09a4-f319-43ff-b058-1cc3abf16872.png">

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
