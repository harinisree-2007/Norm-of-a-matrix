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
# Register No: 212225230093
# Developed By: Harini Sree N


# 1-Norm of a Matrix:

import os
os.environ["OPENBLAS_NUM_THREADS"]='1'
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)




# 2-Norm of a Matrix:

import os
os.environ["OPENBLAS_NUM_THREADS"]='1'
import numpy as np
matrix=np.array(eval(input()))
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))







# Infinity Norm of a Matrix:

import os
os.environ["OPENBLAS_NUM_THREADS"]='1'
import numpy as np
matrix=np.array(eval(input()))
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))





```
## Output:
### 1-Norm of a Matrix:

<img width="1388" height="435" alt="image" src="https://github.com/user-attachments/assets/ec198836-66db-4e6b-b0e5-658911f6fde2" />



### 2-Norm of a Matrix

<img width="1278" height="457" alt="image" src="https://github.com/user-attachments/assets/415afa8e-720e-4d21-a7d3-68450b08b9ec" />


### Infinity Norm of a Matrix

<img width="1187" height="402" alt="image" src="https://github.com/user-attachments/assets/4068aa49-9e54-4a0a-b5a8-2193ff58bdd7" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
