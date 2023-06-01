# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1:
Get the input matrix using np.array()   
## Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
## Step 3:
Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212222100057
# Developed By: Vanitha S
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
norm=np.linalg.norm(mat,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
norm=np.linalg.norm(mat,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
infinity=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(infinity))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Vanitha-SM/Norm-of-a-matrix/assets/119557985/62aa22d2-7774-49ec-8fd3-89d5359589e8)


### 2-Norm of a Matrix
![image](https://github.com/Vanitha-SM/Norm-of-a-matrix/assets/119557985/f491f497-e52a-4bce-9a5b-f25bd58ecca1)


### Infinity Norm of a Matrix
![image](https://github.com/Vanitha-SM/Norm-of-a-matrix/assets/119557985/1ab2dd61-e845-48bf-b55d-4cc2ef2683f4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
