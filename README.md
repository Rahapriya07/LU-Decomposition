# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement
2. From scipy package import lu_factor() and lu_solve().
3. Get two inputs from user and pass it as matrix array.
4. Find lu and pivot value of first marix using lu_factor().
5. Find solution of the matrix by using lu_solve() by passing lu, pivot values as first argument and second matrix as second argument.
6. Print the solution
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Raha Priya Dharshini M
RegisterNumber: 24901069
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
Program to find the LU Decomposition of a matrix.
Developed by: Raha Priya Dharshini M
RegisterNumber: 24901069
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

*/
```

## Output:
![exp 5-1](https://github.com/user-attachments/assets/0225db54-21b0-4afb-b18f-9600341034f0)

![exp 5-2](https://github.com/user-attachments/assets/f2ddb3b2-645f-4add-88bf-f391023892e4)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

