# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1. import numpy as np

Step 2: from scipy package import lu

Step 3: get input from the user

Step 4: print result  

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: HARI PRASATH P
RegisterNumber: 212224230084

import numpy as np
from scipy .linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Sameer Shariff M
RegisterNumber: 212224220085
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy .linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
<img width="904" height="566" alt="image" src="https://github.com/user-attachments/assets/afced7f7-cefa-4029-8098-c12665bdd8ee" />



<img width="908" height="568" alt="image" src="https://github.com/user-attachments/assets/c03e0a6c-3b8f-4d02-8186-37c021dc92b5" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

