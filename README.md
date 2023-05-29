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
# Register No:212222230159
# Developed By:Tharika S
# 1-Norm of a Matrix
Program to find 1-norm of a matrix.
Developed by:Tharika S
RegisterNumber: 212222230159
'''
import numpy as np
array=np.array(eval(input()))
n=np.linalg.norm(array,1)
print("{:.2f}".format(n))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
import numpy as np
array=np.array(eval(input()))
n=np.linalg.norm(array,2)
print("{:.2f}".format(n))

# Infinity Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by:SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot (23)](https://github.com/tharikasankar/Norm-of-a-matrix/assets/119475507/c6876fa7-2d72-42f7-a4a2-9dbc0b9c77ca)


### 2-Norm of a Matrix
![Screenshot (24)](https://github.com/tharikasankar/Norm-of-a-matrix/assets/119475507/02ca6a76-6fb7-4f24-b70d-21effec9300d)


### Infinity Norm of a Matrix
![Screenshot (25)](https://github.com/tharikasankar/Norm-of-a-matrix/assets/119475507/2a14a08e-064c-4c0d-8464-e0822413aa70)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
