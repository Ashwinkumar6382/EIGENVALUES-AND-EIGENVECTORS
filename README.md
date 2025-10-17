# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
 Step1 : Step1 : Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each linear equations and assign in np.array()

Step 3: Using the np.linalg.solve(), we can find the solutions.

Step 4: End the program

## Program:
## Develped by :Ashwin kumar E
## Register No :212224230026
```
puthon
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```



## Output:
<img width="1257" height="248" alt="image" src="https://github.com/user-attachments/assets/48a73e2f-46ed-4e80-8f8d-8815a1b2a46b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
