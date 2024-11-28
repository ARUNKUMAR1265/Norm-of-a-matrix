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
# Register No: 24900773
# Developed By: Arunkumar S
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2024-11-28 203009](https://github.com/user-attachments/assets/3b58af0b-23c0-4e24-9608-2a4e9d48072d)


### 2-Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2024-11-28 203023](https://github.com/user-attachments/assets/af57af92-2ede-43f9-b842-11ab859c42aa)


### Infinity Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2024-11-28 203103](https://github.com/user-attachments/assets/8325c6a7-0b9f-4a36-950b-eb4413b14ee6)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
