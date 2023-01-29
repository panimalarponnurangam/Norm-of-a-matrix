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
# Register No:22009107
# Developed By:panimalar.p
# 1-Norm of a Matrix
import numpy as np 
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

Program to find 2-norm of a matrix.
#Developed by: panimalar.p
#RegisterNumber: 22009107

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

#Developed by: panimalar.p
#RegisterNumber: 22009107
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix

![Screenshot (181)](https://user-images.githubusercontent.com/121490826/214642629-1b1d3bc3-4e40-48b3-92c6-fc51ccfcb870.png)


### 2-Norm of a Matrix

![Screenshot (182)](https://user-images.githubusercontent.com/121490826/214642825-60fd2fc6-1585-4518-ba68-61c9f74512b9.png)


### Infinity Norm of a Matrix

![Screenshot (183)](https://user-images.githubusercontent.com/121490826/214643073-b95085d7-cd97-45ac-a8ee-d066fc04a8b8.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
