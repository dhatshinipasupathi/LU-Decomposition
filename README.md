# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# 5(A)
1. Start the program and import the required libraries, NumPy and SciPy.
2. Read the input matrix and convert it into a NumPy array.
3. Perform LU decomposition using lu(A) to obtain the permutation matrix (P), lower triangular matrix (L), and upper triangular matrix (U).
4. 1. Print the L and U matrices as the output and stop the program.

# 5(B)
1. Start the program and import the required libraries, NumPy and SciPy.
2. Read the input matrix \(A\) and the constant matrix \(B\).
3. Solve the equations using lu_factor(a) to perform LU factorization and lu_solve((l,p),b) to calculate the solution matrix \(X\).
4. Print the solution matrix \(X\) and stop the program.
   
## Program:
# 5(A) To find the L and U matrix
### Program to find L and U matrix using LU decomposition.
### Developed by:DHATSHINI.P 
### RegisterNumber:26010141 
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu

### A = np.array(eval(input()))
### p,l,u = lu(A)
### print(l)
### print(u)
# 5(B) To find the LU Decomposition of a matrix
### Program to solve a matrix using LU decomposition.
### Developed by:DHATSHINI.P 
### RegisterNumber: 26010141
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### To print X matrix (solution to the equations)
### import numpy as np
### from scipy.linalg import lu_factor,lu_solve
### a = np.array(eval(input()))
### b = np.array(eval(input()))
### l,p = lu_factor(a)
### x = lu_solve((l,p),b)
### print(x)

## Output:
# 5(A)
<img width="1137" height="787" alt="image" src="https://github.com/user-attachments/assets/d994be85-5c00-42ad-b945-72e6bfcae209" />
# 5(B)
<img width="1077" height="817" alt="image" src="https://github.com/user-attachments/assets/236997b3-7f9b-418c-a943-844a34d0e2fe" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

