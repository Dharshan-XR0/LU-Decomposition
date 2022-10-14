# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Import the scipy from the library,for lu decomposition.

2. Get the eval input from the user.

3. Assign the value for a,b.

4. printf the program

## Program:
```
(i) To find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: Dharshan v
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
```
(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by:DHARSHAN V 
RegisterNumber: 22003103
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:


![image](https://user-images.githubusercontent.com/113497491/191963197-e5ccd579-3b51-4fca-bd5f-df6b23a24f73.png)


![Ex5CR2](https://user-images.githubusercontent.com/113497491/191964314-5691feca-4834-4f83-9ac5-2b7e911675c3.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

