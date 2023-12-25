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
# Register No:23006823
# Developed By:M GAYATHIRI ROSHINI
# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
norm_of_matrix="{:.2f}".format(result)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
norm_of_matrix="{:.2f}".format(result)
print(norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
norm_of_matrix="{:.2f}".format(result)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/23006823/Norm-of-a-matrix/assets/138971409/cfd417bf-1c45-42fc-bda7-b9afe5cf08c0)

### 2-Norm of a Matrix
![image](https://github.com/23006823/Norm-of-a-matrix/assets/138971409/d4ad8e5d-4c98-4457-b60d-b1f1399e792f)

### Infinity Norm of a Matrix
![image](https://github.com/23006823/Norm-of-a-matrix/assets/138971409/b6095765-9f6b-43e8-a98b-f402d10667e5)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
