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

#Program to find the solution for the given linear equations.
#Developed by: 
#RegisterNumber:
import numpy as np
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
x=np.linalg.solve(a,b)
print(x)

## Output:
[3. 1.]
<img width="1920" height="1080" alt="Screenshot (82)" src="https://github.com/user-attachments/assets/b06cc725-344f-41a1-9ce4-e8716e77be6a" />
<img width="1920" height="1080" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/9fd9cb5b-182c-4d2b-8bc5-e5a84f47184c" />




## Result: 
Thus the solutions for the linear equations are successfully solved using python program

