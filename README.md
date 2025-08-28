# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
Step 1. import numpy as np

Step 2: from scipy package import lu

Step 3: get input from the user

Step 4: print result
## Program:
(i) To find the L and U matrix
Program to find L and U matrix using LU decomposition.
Developed by: Sameer Shariff M
RegisterNumber: 212224220085
```
import numpy as np
from scipy .linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
(ii) To find the LU Decomposition of a matrix
Program to solve a matrix using LU decomposition.
Developed by: Sameer Shariff M
RegisterNumber: 212224220085

```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```
## Output:
<img width="1919" height="1199" alt="Screenshot 2025-08-28 093643" src="https://github.com/user-attachments/assets/22eb6636-54b6-4467-9e40-149cec22df9e" />

<img width="1909" height="1199" alt="image" src="https://github.com/user-attachments/assets/69999c05-15c3-4b01-8d2e-0ef36fc9e69e" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

