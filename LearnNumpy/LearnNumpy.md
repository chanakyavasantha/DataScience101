## Learn Numpy
<hr>
NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, 
along with a large collection of high-level mathematical functions to operate on these arrays.


![Screenshot from 2023-08-16 22-13-00](https://github.com/chanakyavasantha/DATA-SCIENCE/assets/93817654/02cca0c7-24c7-45d4-ab66-ea5e613c72be)

```
import numpy as np
mat1 = [[1,2],[3,4]]
mat2 = [[1,2],[3,4]]
result  = np.add(mat1,mat2)
````

![Screenshot from 2023-08-16 22-23-17](https://github.com/chanakyavasantha/DATA-SCIENCE/assets/93817654/d2485e60-2a49-40ca-9cea-d321a1848d34)
```
import numpy as np
mat1 = [[1,2],[3,4]]
mat2 = [[1,2],[3,4]]
result  = np.add(mat1,mat2)
```

### How to typecast a list into numpy array:
```
import numpy as np
li = [1,2,3]
linp = np.array(li)
print(type(li))
print(type(linp))
```
### Statistical Measures in numpy:
```
arr = np.array([1, 2, 3, 4, 5])
mean = np.mean(arr)
median = np.median(arr)
std_dev = np.std(arr)
max_val = np.max(arr)
min_val = np.min(arr)
```
### Transpose of a matrix in numpy:
![Screenshot from 2023-08-30 18-52-21](https://github.com/chanakyavasantha/DATA-SCIENCE/assets/93817654/1a8f2ffb-0942-4868-b41a-95d87ba47267)
![Screenshot from 2023-08-30 18-52-00](https://github.com/chanakyavasantha/DATA-SCIENCE/assets/93817654/8ee46946-f030-4bf9-aed9-2bbbf29a5818)
```
li = [[1,2,3],[4,5,6]]
li = np.array(li)
print(li.T)
```


