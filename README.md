# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scipy package import lu_factor() and lu_solve().
3. Get two imputs from user and pass it as matrix array.
4. Find lu and pivot value of first matrix using lu_factor().Find solution of the matrix by using lu_solve() by passing lu,piv values as first argument and second matrix as second argument.
5. End the program

## Program:
(i) To find the L and U matrix
```
/*
 '''Program to find L and U matrix using LU decomposition.
Developed by: BALAMURUGAN B
RegisterNumber: 212222230016
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: BALAMURUGAN B
RegisterNumber: 212222230016
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
1.To find the L and U matrix
![mai 5 i](https://github.com/BALA291/LU-Decomposition/assets/120717501/b6e1ae2d-eab9-4860-883d-a8fa8fc8a715)

and 
2. To find the LU Decomposition of a matrix

![mai 5 ii](https://github.com/BALA291/LU-Decomposition/assets/120717501/fbc35c55-110d-4c91-bcaa-d6e446fee5be)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

