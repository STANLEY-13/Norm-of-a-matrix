# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 23014354
# Developed By: STANLEY S

# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/STANLEY-13/Norm-of-a-matrix/assets/148198816/19406f98-dc68-4791-81cd-9e53936d954c)


### 2-Norm of a Matrix

![image](https://github.com/STANLEY-13/Norm-of-a-matrix/assets/148198816/e24c627e-84f0-45d7-9b76-87575b2af772)


### Infinity Norm of a Matrix

![image](https://github.com/STANLEY-13/Norm-of-a-matrix/assets/148198816/3dcbd2b8-a99b-40e1-9c9b-7ba240ed1511)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
