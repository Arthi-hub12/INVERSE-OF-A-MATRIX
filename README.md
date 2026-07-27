# INVERSE-OF-A-MATRIX
## Register: 212225220012
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: ARTHI S A
#RegisterNumber: 212225220012
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[6,2,3],[3,1,1],[10,3,4]])
inverse=np.linalg.inv(matrix)
print(inverse)
~~~

## Output:

<img width="1065" height="623" alt="Screenshot 2026-07-27 210742" src="https://github.com/user-attachments/assets/690ad85b-fcd6-4add-897a-cb5da0ed2a43" />
<img width="1072" height="256" alt="Screenshot 2026-07-27 210758" src="https://github.com/user-attachments/assets/35de7c2b-16aa-4e9f-b11d-016ad43170c0" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

