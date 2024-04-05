# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy package
2. from scipy.linalg import lu
3. solve using scipy.linlag(variable)
4. End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.

Developed by: E Prasanth

RegisterNumber: 212221233002
'''

import numpy as np

from scipy.linalg import lu

A = np.array(eval(input()))

P, L, U = lu(A)

print(L)

print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.

Developed by: E Prasanth

RegisterNumber: 212221233002
'''
import numpy as np

from scipy.linalg import lu

A = np.array(eval(input()))

B = np.array(eval(input()))

C = np.linalg.solve(A,B)

print(C)
```

## Output:
![Screenshot (18)](https://github.com/PrasanthE2001/LU-Decomposition/assets/114572171/d840fdb4-a3c6-448e-8a76-420c29bdb063)

![Screenshot (19)](https://github.com/PrasanthE2001/LU-Decomposition/assets/114572171/8cfb6c1e-b6ea-4347-ae27-db60a33bae7b)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

