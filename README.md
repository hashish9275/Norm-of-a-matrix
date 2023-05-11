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
```
Python
# Register No:K R HASHISH VIDYA SAGAR
# Developed By: 212222230047

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:

### 1-Norm of a Matrix
![ma xp7 i](https://github.com/hashish9275/Norm-of-a-matrix/assets/118707521/83f250ea-495b-4592-882f-48fcf65ab5d6)

### 2-Norm of a Matrix
![ma xp7 ii](https://github.com/hashish9275/Norm-of-a-matrix/assets/118707521/fba1784d-65a9-4e0a-bf28-a57423b83b3d)


### Infinity Norm of a Matrix
![ma xp7 iii](https://github.com/hashish9275/Norm-of-a-matrix/assets/118707521/ba547745-8f44-4a24-9d3e-0eb80ebaa9c7)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
