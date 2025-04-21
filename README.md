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
'''
# 1-Norm of a Matrix
'''
Program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by : Gayathri S
Register number: 212224230073

'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Gayathri S
RegisterNumber: 212224230073
'''
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# Infinity Norm of a Matrix

'''
Program to find Infinity norm of a matrix.
Developed by: Gayathri S
RegisterNumber: 212224230073
'''
import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))







```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-21 155557](https://github.com/user-attachments/assets/ac304aa4-065c-4808-a8ec-3f9b8e6588ad)


### 2-Norm of a Matrix

![Screenshot 2025-04-21 155614](https://github.com/user-attachments/assets/f0b543ea-51bd-46a7-b171-54c8eea960e3)


### Infinity Norm of a Matrix

![Screenshot 2025-04-21 155627](https://github.com/user-attachments/assets/22e4dd17-0f20-4698-b057-7da43fdd2d7e)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
