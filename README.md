# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: Import the required library numpy as np.
###Step 2: Define the matrix as a 2D NumPy array with the given elements.
###Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
###Step 4: Print the rank of the matrix.

## Program:
#Program to find the rank of a matrix.
#Developed by: Aashik
#RegisterNumber: 212225040005
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(A)
print(rank)
## Output:
<img width="1523" height="806" alt="Screenshot 2026-06-02 130706" src="https://github.com/user-attachments/assets/a45c7b9a-1252-4988-b1de-153030ea3198" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

