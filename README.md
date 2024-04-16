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
Program to find the L and U matrix.
Developed by: MANOJ M
RegisterNumber: 212223231022
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: MANOJ M
RegisterNumber: 212223231022
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![image](https://github.com/Manoj0079940/LU-Decomposition/assets/149366208/996b25f9-c57a-4fa2-84ca-c3f34a16593e)
![image](https://github.com/Manoj0079940/LU-Decomposition/assets/149366208/7f066a71-1087-4d0a-a26d-846066630fba)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

