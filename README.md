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
# Register No:212225230293
# Developed By:Vemareddygari Pallavi
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1350" height="845" alt="image" src="https://github.com/user-attachments/assets/abbbf01e-0261-4b8e-9255-bc0d15174413" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1091" height="724" alt="image" src="https://github.com/user-attachments/assets/7919013c-6fc7-45f6-85b8-a71d3f4101fc" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1137" height="863" alt="image" src="https://github.com/user-attachments/assets/13ad13ab-2be7-4b6c-8bf4-c951bacc48ef" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
