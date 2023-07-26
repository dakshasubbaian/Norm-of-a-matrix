# Norm of a matrix
## AIM:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## EQUIPMENTS REQUIRED::
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## AGORITHM:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## PROGRAM:
```
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: Daksha Subbaian
RegisterNumber: 23003584
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Daksha Subbaian
RegisterNumber: 23003584
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
'''
Program to find infinity of a matrix.
Developed by: Daksha Subbaian
RegisterNumber: 23003584
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## OUTPUT:
### 1-Norm of a Matrix

![output](/output07\)1..png)

### 2-Norm of a Matrix
![output](/output07\)2..png)

### 3-Infinity Norm of a Matrix
![output](/output07\)3..png)

## RESULT:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
