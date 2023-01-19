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
# Register No:shaik sameer basha
# Developed By:22004926
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: shaik sameer basha
RegisterNumber: 22004926
'''
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![norm1_output](https://user-images.githubusercontent.com/118707756/213446407-d1d5f9b6-5f0a-44ba-8272-5909523e37de.png)
### 2-Norm of a Matrix
![norm2_output](https://user-images.githubusercontent.com/118707756/213446861-1b9c4463-f43b-4840-974d-bf180a0cb5d1.png)
### Infinity Norm of a Matrix
![norm3_output](https://user-images.githubusercontent.com/118707756/213447187-fb52fd99-6a1e-44f6-8e8c-f129e1744d6f.png)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
