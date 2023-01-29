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
# Register No:22001588
# Developed By:BHARATHGANSH.S
# 1-Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix

```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![outputa](https://user-images.githubusercontent.com/119478098/215316976-48f2c0ae-2385-4b6f-b47a-909c42311c8c.png)


### 2-Norm of a Matrix
![outputb](https://user-images.githubusercontent.com/119478098/215317149-294055d3-5c22-484a-9a1a-65ed44d9df2e.png)

### Infinity Norm of a Matrix
![outputc](https://user-images.githubusercontent.com/119478098/215317010-393c4a4a-4b4d-4958-ba57-53fd88d1a4ec.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
