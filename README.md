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
'''Program to find L and U matrix using LU decomposition.
Developed by: A.VIJIYALAKSHMI
RegisterNumber: 25017569
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

```

## Output:
(i)  <img width="1228" height="697" alt="Screenshot 2025-11-19 132845" src="https://github.com/user-attachments/assets/d4c277f5-eaa7-41c8-99b4-8e037996bf7f" />
     <img width="1236" height="580" alt="Screenshot 2025-11-19 132823" src="https://github.com/user-attachments/assets/cf240a2d-1fcb-4e4d-841a-7fa9eff58335" />

(ii) <img width="1234" height="639" alt="Screenshot 2025-11-19 132907" src="https://github.com/user-attachments/assets/61f96dc4-008c-4365-b039-f529f9b985ef" />
    <img width="1238" height="316" alt="Screenshot 2025-11-19 132925" src="https://github.com/user-attachments/assets/daf48e5c-e2f9-48c3-8f2c-a4306c6eddd9" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

