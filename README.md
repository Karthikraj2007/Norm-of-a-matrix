# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```
Program to find 2-norm of a matrix.
Developed by: Karthikraj C
RegisterNumber: 212224230117

import numpy as np
matrix=np.array(eval(input()))
res=np.linalg.norm(matrix,2)
print("{:.2f}".format(res))
```
## Output:
![alt text](<Screenshot 2025-05-21 235046.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
