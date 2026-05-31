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
### Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Given matrix
matrix = [[5, -3, -10],
          [2, 2, -3],
          [-3, -1, 5]]

# Find rank of matrix
rank = np.linalg.matrix_rank(matrix)

# Print result
print(rank)
## Output:

<img width="629" height="823" alt="image" src="https://github.com/user-attachments/assets/55d3b37d-9775-4a60-8deb-6af24f3d521e" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

