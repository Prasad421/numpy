import numpy as np

# create a 1-dimensional array
a = np.array([1, 2, 3])
print(a)
# [1 2 3]

# create a 2-dimensional array
b = np.array([[1, 2, 3], [4, 5, 6]])
print(b)
# [[1 2 3]
#  [4 5 6]]

# create an array of zeros
c = np.zeros((3, 3))
print(c)
# [[0. 0. 0.]
#  [0. 0. 0.]
#  [0. 0. 0.]]

# create an array of ones
d = np.ones((3, 3))
print(d)
# [[1. 1. 1.]
#  [1. 1. 1.]
#  [1. 1. 1.]]

# create an array of random values
e = np.random.random((3, 3))
print(e)
# [[0.48253513 0.66048497 0.88368788]
#  [0.68244932 0.70357595 0.60393774]
#  [0.56970596 0.56802334 0.95656473]]

# indexing and slicing
a = np.array([1, 2, 3, 4, 5, 6])
print(a[1])      # 2
print(a[1:3])    # [2 3]

# reshaping
a = np.array([1, 2, 3, 4, 5, 6])
a = a.reshape((2, 3))
print(a)
# [[1 2 3]
#  [4 5 6]]

# transposing
a = np.array([[1, 2, 3], [4, 5, 6]])
a = a.T
print(a)
# [[1 4]
#  [2 5]
#  [3 6]]
