# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linag import lu.
2. Get input from user and print L and U matix by 'print'
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as'X' include the package in that variable
4. print the variale 'X'

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Rohiit.A.S
RegisterNumber: 23010688
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Rohiit.A.S
RegisterNumber: 23010688
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![exp5(1)](https://github.com/Rohiit2005/LU-Decomposition/assets/138849178/b105873b-dc12-4e3b-84cc-43ec047ce3ab)
![exp5(2)](https://github.com/Rohiit2005/LU-Decomposition/assets/138849178/625e990b-a15d-4b62-be96-362ce7b224fc)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

