# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:DHARSHAN V 
RegisterNumber: 22003103
*/
```
import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)

```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)


## Output:

![Ex5CR1](https://user-images.githubusercontent.com/113497491/191962965-5ee703b7-c199-4c84-a79b-6b5ea6909916.png)


![Ex5CR2](https://user-images.githubusercontent.com/113497491/191962995-b4062c4d-f8cb-4873-b445-8409216805c3.png)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

