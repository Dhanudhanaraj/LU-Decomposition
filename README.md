# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in function for calculations.

2.Get the input from the user.

3.Using the solution=lu_solve(res,B),we can find the solution.

4.End the program.

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by:Dhanumalya.D 
RegisterNumber:22008657 
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by:Dhanumalya.D 
RegisterNumber:22008657
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
!["Output"](/LU%20matrix.png)
!["Output"](/LU%20decom.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

