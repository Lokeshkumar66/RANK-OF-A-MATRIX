# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: L.LOKESH KUMAR
#RegisterNumber: 212225040209
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array([[5, -3, -10],
              [2,  2,  -3],
              [-3, -1,  5]])
result= np.linalg.matrix_rank(A)
print(result)
~~~
## Output:
<img width="422" height="182" alt="Screenshot 2026-08-16 153116" src="https://github.com/user-attachments/assets/71015c0c-ebd6-4594-87e6-4da10fcc7ed1" />
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

