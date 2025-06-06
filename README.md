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
# Register No:212224240076
# Developed By:CS KIRAN KUMAR 
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-22 113404](https://github.com/user-attachments/assets/83bf5764-29dd-4068-8864-7cbeb68d8349)


### 2-Norm of a Matrix

![Screenshot 2025-04-22 113423](https://github.com/user-attachments/assets/02a818cc-3a8e-497a-9c25-eed6447fb977)


### Infinity Norm of a Matrix

![Screenshot 2025-04-22 113437](https://github.com/user-attachments/assets/41c839e3-2f1b-49f4-a4b4-ecab12122a2b)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
