# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### step 1:
Get the input matrix using np.array()   
### step 2:
Find the 2-norm of the matrix using np.linalg.norm()
### step 3:
Print the norm of the matrix in two decimal places.
## Program:
```Python
# Developed By:Naveenkanthan L
# Register No:23007705
# 1-Norm of a Matrix
import numpy as np
a=eval(input())
print("%.2f"%np.linalg.norm(a,ord=1))



# 2-Norm of a Matrix
import numpy as np
a=eval(input())
print("%.2f"%np.linalg.norm(a,ord=2))



# Infinity Norm of a Matrix
import numpy as np
a=eval(input())
print("%.2f"% np.linalg.norm(a,np.inf))




```
## Output:
### 1-Norm of a Matrix
<br><img width="727" alt="290121653-2015d30c-e5c4-4058-b0c7-a04b363e8042" src="https://github.com/Naveen1825/Norm-of-a-matrix/assets/138969868/84b057cd-e33d-407e-98d3-0c7c3f9b8bd5">

<br>
<br>

### 2-Norm of a Matrix
<br><img width="628" alt="290121750-7f5e1ac2-9792-48c2-81ab-450d8be31b59" src="https://github.com/Naveen1825/Norm-of-a-matrix/assets/138969868/aa4e9dc7-b167-4f08-95e3-e3b09667c116">

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="614" alt="290122023-3613c171-fed2-41ee-a906-be9b2db617ae" src="https://github.com/Naveen1825/Norm-of-a-matrix/assets/138969868/c3e952dc-b45a-4b2f-b42d-116569a147ba">

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
