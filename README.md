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
Developed by: SANJAY SRISANTH V
RegisterNumber: 212225040375
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SANJAY SRISANTH V
RegisterNumber: 212225040375

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![lu decomposition]()
<img width="1045" height="611" alt="Screenshot 2026-05-28 140930" src="https://github.com/user-attachments/assets/e6754262-872a-4aa0-a309-8d7bf53c4598" />

<img width="902" height="568" alt="{988E4A7E-2B93-4A9A-9CC9-9B1421B32465}" src="https://github.com/user-attachments/assets/4b03e7d3-a9d9-4908-8975-f2d410706436" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

