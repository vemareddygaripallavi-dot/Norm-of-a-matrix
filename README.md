# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
	4. End the program.
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
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))


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
<img width="1081" height="521" alt="image" src="https://github.com/user-attachments/assets/8521c762-f4b0-4c62-971b-cc0916212274" />

<img width="841" height="379" alt="image" src="https://github.com/user-attachments/assets/deaab6b8-9200-4633-9881-1c29313970e2" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
