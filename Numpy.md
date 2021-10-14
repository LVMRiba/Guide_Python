import numpy as np

#### ENTRADAS
```
weights = [0.3, 0.2, 0.5]
grades = np.array([73, 67, 43])
```

#### TIPO
```
print(type(grades))
```

<class 'numpy.ndarray'>

#### MÉDIA PONDERADA (dot)
```
np.dot(grades, weights)
```

56.8

#### REMODELAR MATRIZ (reshape)

```
arr1 = np.array([3, 4, 5])
arr2 = np.array([[7, 6, 4], [9, 8, 6], [8, 1, 5], [2, 5, 8]])
arr3 = np.array([[[7, 6, 4], [9, 8, 6]],
                [[8, 1, 5], [2, 5, 8]]])             
```

##### 2D array (matrix)
```
print(arr1.shape)
```

(3,)

##### 1D array (vector)
```
print(arr2.shape)
```

(4, 3)

##### 3D array
```
print(arr3.shape)
```

(2, 2, 3)

#### MATMUL
```
print(np.matmul(arr2, weights))
```

[5.3 7.3 5.1 5.6]

