## EX4- EIGENVALUES-AND-EIGENVECTORS
## Date-22.08.2023
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module to use the built function.
### Step 2: Prepare the lists from each equation and assign np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the program.

## Program:
```
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Kishorekumar22060/EIGENVALUES-AND-EIGENVECTORS/assets/141472136/9371e64b-84ac-4ab1-b7d8-f450aafa920a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
