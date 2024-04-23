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
# Register No:
# Developed By:
# 1-Norm of a Matrix
'''
program to find 1-norm of a matrix.
Developed by:SANTHOSH KUMAR B
Register number:212223230193
'''
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SANTHOSH KUMAR B
RegisterNumber: 212223230193
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix
'''
Program to find Infinity-norm of a matrix.
Developed by: SANTHOSH KUMAR B
RegisterNumber: 212223230193
'''
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))





```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/Santhoshstudent/Norm-of-a-matrix/assets/145446853/01c4a48b-0e84-4dd1-83a4-f9e6fb81e5bc)



### 2-Norm of a Matrix

![Screenshot 2024-04-23 114932](https://github.com/Santhoshstudent/Norm-of-a-matrix/assets/145446853/bb7cb7a7-b270-4038-8c73-1f61ce444c7b)




### Infinity Norm of a Matrix

![image](https://github.com/Santhoshstudent/Norm-of-a-matrix/assets/145446853/826c422f-412a-474e-99bb-a9ce7de84dee)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
