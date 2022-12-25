# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End of program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Aakashraj M
#RegisterNumber: 22008579

import numpy as np
a=np.array([[2,1,1,],[1,1,1],[1,-1,2]])
inverse=np.linalg.inv(a)
print(inverse)
```

## Output:
![Ex-3 Output](https://user-images.githubusercontent.com/121117266/209474147-5e8b4915-f7a1-40fa-84ff-01a9473d8c16.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

