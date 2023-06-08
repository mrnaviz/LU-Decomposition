# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import maths as numpy
2.give the input values
3.use eval input
4.print the L and U matrix 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NAVEEN KUMAR.B
RegisterNumber: 212222230091
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: NAVEEN KUMAR.B
RegisterNumber: 212222230091
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv = lu_factor(A)
x=lu_solve((lu,piv),B)
print(x) 
*/
```

## Output:
![maths ex05(1)](https://github.com/mrnaviz/LU-Decomposition/assets/123350791/d675992c-fd5b-4286-90b5-cdefc50f1b76)
![maths ex05](https://github.com/mrnaviz/LU-Decomposition/assets/123350791/021b529e-49b1-4121-a518-8ea85630e4ee)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

