# EIGENVALUES-AND-EIGENVECTORS
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
End the program.
## Program:
```
import numpy as np
A = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot 2023-09-24 200737](https://github.com/swethaselvarajm/EIGENVALUES-AND-EIGENVECTORS/assets/119525603/a091eaac-54af-4e89-b9ec-264936f833e4)

## Result:
Thus,the Eigenvalue and Eigenvector is successfully solved using python program.
