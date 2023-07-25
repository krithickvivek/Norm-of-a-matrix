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
# Register No: Krithick Vivekananda
# Developed By: 23009445
# 1-Norm of a Matrix

'''Developed by: Krithick Vivekananda
RegisterNumber: 23009445'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)


# 2-Norm of a Matrix
'''Developed by: Krithick Vivekananda
RegisterNumber: 23009445'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)


# Infinity Norm of a Matrix
'''Developed by: Krithick Vivekananda
RegisterNumber: 23009445'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)


```
## Output:
### 1-Norm of a Matrix

![norm1](norm1.png)

### 2-Norm of a Matrix

![norm2](norm2.png)


### Infinity Norm of a Matrix

![norminf](norminf.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
