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
## Program:import numpy as np

# Define the coefficients matrix A and the constants vector b
A = np.array([[5, -3, -10], [2, 2, -3], [-3, -1, 5]])
b = np.array([-9, 4, -1])

# Solve the system of linear equations using NumPy's linalg.solve function
solution = np.linalg.solve(A, b)

# Print the solution
print(solution)

## Output:
![image](https://github.com/user-attachments/assets/8d9d773c-8a00-4542-9c8e-b44f1919ae89)
![image](https://github.com/user-attachments/assets/40af19cd-a824-44be-9a9c-bfcaad594de0)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

