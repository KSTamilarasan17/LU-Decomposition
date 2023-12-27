# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scipy package import lu().
3.  Get input from user and pass it as an array.
4. Get P, L, U matrix using lu()
5. Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: TAMILARASAN K S.
RegisterNumber: 23000080
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: TAMILARASAN K S.
RegisterNumber: 23000080
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![Screenshot 2023-12-27 082156](https://github.com/KSTamilarasan17/LU-Decomposition/assets/138849236/0df9510f-e93e-4045-a522-12e17ce158a2)
![Screenshot 2023-12-27 082208](https://github.com/KSTamilarasan17/LU-Decomposition/assets/138849236/47ddf92b-0997-49b8-aa9a-253f2483e833)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

