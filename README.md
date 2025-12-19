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
# Register No: 25017522
# Developed By: Karthi V
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")



# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")



# 3-Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm3=np.linalg.norm(A,np.inf)
print(f"{norm3:.2f}")





```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (135)" src="https://github.com/user-attachments/assets/b97ab8a8-d6ba-4319-afbf-708d2dd2060b" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (136)" src="https://github.com/user-attachments/assets/e0dba752-5637-4c79-a528-a753d1600d3e" />

<br>
<br>
<br>

### 3-Infinity Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (137)" src="https://github.com/user-attachments/assets/a14b143e-a83f-4b88-9bae-e5db30013ac6" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
