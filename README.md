# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program
## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by:vishal r 
RegisterNumber: 212225240493
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
*
Program to find the LU Decomposition of a matrix.
Developed by:vishal.r 
RegisterNumber: 212225240493
*/
```

## Output:
<img width="1075" height="410" alt="Screenshot 2026-03-25 212139" src="https://github.com/user-attachments/assets/dd441322-8df2-4157-b3b3-787203309ece" />
<img width="1218" height="911" alt="Screenshot 2026-03-25 212300" src="https://github.com/user-attachments/assets/b0e35b8e-60f9-4de6-8772-04170bbb1b08" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

