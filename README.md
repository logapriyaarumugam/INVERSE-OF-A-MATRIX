# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Start the program.
### Step 2: Import the NumPy library and get the matrix as input.
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: Display the inverse of the matrix and stop the program.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: LOGAPRIYA A
#RegisterNumber:212225040202
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="878" height="231" alt="image" src="https://github.com/user-attachments/assets/e0849a76-fff3-4840-8d51-3884f1f5d2e8" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

