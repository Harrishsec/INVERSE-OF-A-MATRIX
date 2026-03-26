# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.Start the program and input the square matrix.
2.Find the determinant of the matrix.
3.Check determinant ≠ 0 (otherwise inverse not possible).
4.Compute inverse using suitable method (e.g., linalg.inv()).
5.Display the inverse matrix and stop.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Harrish P    
#RegisterNumber:212224230088
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(A)
print(b)
```
## Output:
<img width="1919" height="1048" alt="image" src="https://github.com/user-attachments/assets/8723d562-89e2-463e-91fe-8b2c2c1b090c" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

