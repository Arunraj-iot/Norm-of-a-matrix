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
# Register No:212224110006
# Developed By:ARUNRAJ R
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix="{:2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname : ARUNRAJ R
RegisterNumber: 212224110006
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: ARUNRAJ R
RegisterNumber: 212224110006
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1173" height="960" alt="Screenshot 2025-09-18 085953" src="https://github.com/user-attachments/assets/71f5b488-56a4-41cf-8ded-3d771fbfa405" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="1293" height="951" alt="Screenshot 2025-09-18 090008" src="https://github.com/user-attachments/assets/6b6497f3-4f60-4bd1-8191-aa5c2c84f7e1" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1234" height="942" alt="Screenshot 2025-09-18 090022" src="https://github.com/user-attachments/assets/ebd6bc1c-2e3d-46d4-95f4-dfed87fdb81a" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
