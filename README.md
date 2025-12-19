# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. ## step 1: Import the numpy module to use built-in function for calculation
2. ## step 2: Prepare the list from matrix and assign in np.array
3. ## step 3: Using lu_solve and lu_factor we can find the solution
4. ## step 4: End the program

## Program:
(i) To find the L and U matrix
Program to find the L and U matrix.
Developed by: SANTHI P
RegisterNumber: 25004254
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
Program to find the LU Decomposition of a matrix.
Developed by: SANTHI P 
RegisterNumber: 25004254
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/71c41a25-bcef-4342-908e-a41025a08429" />
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/7a3240ab-9cfb-473d-829f-40b64cb1713e" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

