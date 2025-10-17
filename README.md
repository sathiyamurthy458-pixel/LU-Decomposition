# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program
   

## Program:
(i) To find the L and U matrix
```import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: sathiya murthy k
RegisterNumber: 25006776
*/
```
(ii) To find the LU Decomposition of a matrix
```import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B-np.array(eval(input()))
lu,pivot lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
/*
Program to find the LU Decomposition of a matrix.
Developed by: sathiya murthy k
RegisterNumber: 25006776
*/
```

## Output:
![lu decomposition]()


<img width="795" height="788" alt="Screenshot 2025-10-17 104711" src="https://github.com/user-attachments/assets/6d1218e8-b3d5-4c90-bb63-f11551fc0978" />


<img width="1216" height="571" alt="Screenshot 2025-10-17 104741" src="https://github.com/user-attachments/assets/753e78bf-b086-4aef-ab63-3b2d0216dd90" />



<img width="732" height="771" alt="Screenshot 2025-10-17 104752" src="https://github.com/user-attachments/assets/9509ba10-f4a8-41d7-a696-f75597d743d9" />


<img width="1131" height="295" alt="Screenshot 2025-10-17 104805" src="https://github.com/user-attachments/assets/efbdbb99-bd20-4522-9e73-9528b90ca0f8" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

