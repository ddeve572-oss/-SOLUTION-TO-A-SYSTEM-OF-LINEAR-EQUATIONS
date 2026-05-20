# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np 
A=[[1,-3],[3,1]] 
B=np.array([0,10]) 
C=np.linalg.solve(A,B) 
print(C)

```
## Output:
<img width="1240" height="511" alt="Screenshot 2026-05-20 124557" src="https://github.com/user-attachments/assets/3d0c1d0e-4fc1-4447-a76f-5832369e78b9" />
<img width="1291" height="208" alt="Screenshot 2026-05-20 124619" src="https://github.com/user-attachments/assets/3df09a3c-129c-4cfd-a713-02f5983e6c6e" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

