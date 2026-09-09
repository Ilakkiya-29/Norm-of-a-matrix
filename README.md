# Norm of a matrix

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
	#1. Algorithm for 1-Norm of a Matrix
	Step 1: Start the program.
	Step 2: Import the required os and numpy libraries.
	Step 3: Set the environment variable OPENBLAS_NUM_THREADS to "1".
	Step 4: Get the matrix input from the user and convert it into a NumPy array.
	Step 5: Calculate the 1-Norm of the matrix using np.linalg.norm(mat, 1).
	Step 6: Format the result to two decimal places.
	Step 7: Display the 1-Norm of the matrix.
	Step 8: Stop the program.
	
	#2. Algorithm for 2-Norm of a Matrix
	Step 1: Start the program.
	Step 2: Import the required os and numpy libraries.
	Step 3: Set the environment variable OPENBLAS_NUM_THREADS to "1".
	Step 4: Get the matrix input from the user and convert it into a NumPy array.
	Step 5: Calculate the 2-Norm of the matrix using np.linalg.norm(mat, 2).
	Step 6: Format the result to two decimal places.
	Step 7: Display the 2-Norm of the matrix.
	Step 8: Stop the program.

	#3. Algorithm for Infinity Norm of a Matrix
	Step 1: Start the program.
	Step 2: Import the required os and numpy libraries.
	Step 3: Set the environment variable OPENBLAS_NUM_THREADS to "1".
	Step 4: Get the matrix input from the user and convert it into a NumPy array.
	Step 5: Calculate the Infinity Norm of the matrix using np.linalg.norm(mat, np.inf).
	Step 6: Format the result to two decimal places.
	Step 7: Display the Infinity Norm of the matrix.
	Step 8: Stop the program.
	
## Program:
```Python
# Register No: 212225040130
# Developed By: Ilakkiya K
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 3-Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"  
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix) 
```

## Output:
### 1-Norm of a Matrix
<img width="747" height="807" alt="image" src="https://github.com/user-attachments/assets/4572018f-3b1c-42cd-a722-0e4d09210227" />

### 2-Norm of a Matrix
<img width="817" height="818" alt="image" src="https://github.com/user-attachments/assets/c9b2680b-c8d6-402e-b2c6-df4cc2d09339" />

### Infinity Norm of a Matrix
<img width="828" height="812" alt="image" src="https://github.com/user-attachments/assets/179c12f2-736f-447a-a186-0ef5a4d45d61" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
