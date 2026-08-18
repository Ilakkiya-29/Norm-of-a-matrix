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
<img width="603" height="205" alt="image" src="https://github.com/user-attachments/assets/be421be0-7b73-467a-a6fb-51e5fc87f454" />

### 2-Norm of a Matrix
<img width="612" height="257" alt="image" src="https://github.com/user-attachments/assets/2cbd593a-c535-438c-a19c-ceb21fe8e9bd" />

### Infinity Norm of a Matrix
<img width="610" height="217" alt="image" src="https://github.com/user-attachments/assets/02d8d772-e129-4ea0-888c-521e6745dc4f" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
