# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
# Date:
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
# Questiom:
  wrtie a program to find a solution to a system of linear equation 5x-3y-10z=9,2x+2y-3z=4,-3x-y+5z=-1
## Program:
```
Developed by:yogavarma.B
RegisterNumber:2305002026
```
```python
 import numpy as np
 A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
 rank=np.linalg.matrix_rank(A)
 print(rank)
```

## Output:
![image](https://github.com/kavipriyasp07/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155508590/352a0a84-4dcd-4ef3-af43-0ddccd99eb94)



## Result: 
Thus the solutions for the linear equations are successfully solved using python program

