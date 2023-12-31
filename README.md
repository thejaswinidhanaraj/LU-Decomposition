# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation.
2. Type the program to be executed.
3. Using the lu(),we can find the solutions.
4. Print the value and end the program.
   

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: THEJASWINI
RegisterNumber: 212223110059
import numpy as nu
from scipy.linalg import lu
a=nu.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: THEJASWINI
RegisterNumber: 212223110059
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
*/

```

## Output:
![image](https://github.com/thejaswinidhanaraj/LU-Decomposition/assets/148514511/bd0ab692-71ee-4179-9f7e-84449bc7d254)
![image](https://github.com/thejaswinidhanaraj/LU-Decomposition/assets/148514511/ff84e940-c008-409b-9824-e2e70d77e575)


![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

