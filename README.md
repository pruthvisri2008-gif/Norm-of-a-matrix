
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
# Register No:212225220077
# Developed By:Pruthvisri A
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
<img width="1920" height="1080" alt="Screenshot (202)" src="https://github.com/user-attachments/assets/2a593bcf-0ab4-49d7-9fd7-f2f8f9a0ff36" />


### 2-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (203)" src="https://github.com/user-attachments/assets/e8fd4c03-4f02-43d9-a65b-5a13c62a8bd7" />

### Infinity Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (204)" src="https://github.com/user-attachments/assets/e001b370-3a85-46f6-8492-3148f480a015" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
