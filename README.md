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
# Register No:212222240108
# Developed By: THANJIYAPPAN.K
# 1-Norm of a Matrix
Program to find 1-norm of a matrix.

import numpy as np

mat = np.array(eval(input()))
ans =np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np

# Type your code here
mat = np.array(eval(input()))
ans =np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np

# Type your code here
mat = np.array(eval(input()))
ans =np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/22009011/Norm-of-a-matrix/assets/118343461/cf272fea-aafd-44d1-9149-08397de7ac60)


### 2-Norm of a Matrix
![image](https://github.com/22009011/Norm-of-a-matrix/assets/118343461/b611432d-4c3f-4ad2-be99-fcd4403b6988)


### Infinity Norm of a Matrix
![image](https://github.com/22009011/Norm-of-a-matrix/assets/118343461/85643aa1-0bc4-4564-bca9-f0c2ca908f9f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
