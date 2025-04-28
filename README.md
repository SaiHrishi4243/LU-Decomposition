# LU Decomposition 

## AIM:

To write a program to find the LU Decomposition of a matrix.

## Equipments Required:

1. Hardware – PCs

2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

### Step1 :

Import the numpy module to use the built-in functions for calculation

### Step 2: 

Prepare the lists from each linear equations and assign in np.array()

### Step 3: 

Using scipy.linalg , we can find the LU Decomposition for a matrix

### Step 4: 

End the program

## Program:
(i) To find the L and U matrix
```python

'''Program to find L and U matrix using LU decomposition.
Developed by: Sai Hrishi M
RegisterNumber: 21224240140
'''

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```python

'''Program to solve a matrix using LU decomposition.
Developed by: Sai Hrishi M
RegisterNumber: 212224240140
'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

```

## Output:

### Output (i) :

![Screenshot 2025-04-29 003259](https://github.com/user-attachments/assets/b345a3c1-57af-491c-beb5-a358da11afac)

### Output (ii) :

![Screenshot 2025-04-29 003312](https://github.com/user-attachments/assets/b4474d88-3b6f-4a97-9cec-46463b937147)

## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

