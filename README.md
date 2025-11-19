# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.inv(), we can find the solutions.
### Step 4: 
End the program

## Program:
import numpy as np
A = np.array([[1, 0, 3],[-1, 2, -2],[2, 3, -1]])
x= np.linalg.inv(A)
print(x)
## Output:
<img width="1920" height="1080" alt="Screenshot 2025-11-19 202938 - Copy" src="https://github.com/user-attachments/assets/079dbba2-ec4e-41e4-837f-95396ee8e5a2" />
## Result:
Thus the inverse of given matrix is successfully solved using python program

