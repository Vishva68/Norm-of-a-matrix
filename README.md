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
# Register No:Vishvanandh N
# Developed By:212224240186
# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)



# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input())) 
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))



# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input())) 
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result)) 




```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2025-05-10 092049](https://github.com/user-attachments/assets/e1f9f434-a1bd-4b52-a1f1-549ff6d226c9)

<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2025-05-10 092041](https://github.com/user-attachments/assets/a3065c22-af28-400c-893e-b44c50673bf9)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2025-05-10 092019](https://github.com/user-attachments/assets/21d522b5-83d8-40fa-b28f-747a0c7ca59e)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
