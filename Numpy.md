import numpy as np

#### ENTRADAS
weights = [0.3, 0.2, 0.5]
grades = np.array([73, 67, 43])

#### TIPO
print(type(grades))

Out: "<class 'numpy.ndarray'>"

#### MÉDIA PONDERADA (dot)
np.dot(grades, weights)

Out: "56.8"

print(type(grades))
