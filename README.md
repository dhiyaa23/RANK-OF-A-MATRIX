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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
r=np.linalg.matrix_rank(a)
print(r)
## Output:
<img width="1286" height="845" alt="math 2" src="https://github.com/user-attachments/assets/7fdb2be4-34b4-463f-b906-ccacf346ac27" />
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

