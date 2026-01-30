# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1:
we have to intialise program using import numpy to perform mathematical calculation
## Step 2:
The input from the user is stored in the variable a
## Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
## Step 4: 
end of the program
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: Piruthiviraj G
#RegisterNumber:25016420
#The number of linearly independent rows or columns in a matrix
# is known as its rank
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(a)
print(rank)
```
## Output:
<img width="1212" height="866" alt="image" src="https://github.com/user-attachments/assets/eb312ac6-66ec-4b5d-97b9-193ece1cb7dd" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

