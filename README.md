# Numpy-Tutorials
📚 A repository that contains all the basics of numpy in a structured manner.😊🏆


# Advantages of Numpy
- Numpy provides efficient storage.
- It also provides better ways of handeling data for processing.
- It is fast and easy to learn.
- Uses less memory to store data.


# How to import numpy
`import numpy as np`

# How to create a numpy array
- arr=np.array([x1, x2, x3,...., xn])
- arr= np.array([[1,2,3],[4,5,6],[7,8,9]])  In this way we a=can create 2D array.
- to diaplay the array use `arr`

# Some important functions of numpy
- `arr.dtype` It gives the datatype of the array (eg. int32, int64, etc)
- `rng=np.arange(n)` It gives an array from 0 to n-1 (eg. [1, 2, 3,...., n-1])
- `lspace=np.linspace(a,b,c)` It gives the array from range a to b with c values absutute difference (eg. lspace=np.linspace(1,5,12) it gives array([1.        , 1.36363636, 1.72727273, 2.09090909, 2.45454545,
       2.81818182, 3.18181818, 3.54545455, 3.90909091, 4.27272727,
       4.63636364, 5.        ])  ).

- `arr=arr.reshape(a,b)` If the array has n values than the function gives a matrix is  a X b here b must be divisible bt n.
- `arr.shape` It gives the size of the matrix (eg. N X M).
- `arr.size` it gives the size of the array or matrix.
- `zeros=np.zeros((N,M))` Creating a matrix of size  N X M with values 0.
- `arr=arr.ravel()` It uses to convert matrix to list eg. arr=[[1,2],[3,4]] => arr=[1,2,3,4].
- `ar=np.array(x)` if x is a list than the function converts the list to numpy array.
- `ar.tolist()` It uses to convert numpy array to list.
- `np.count_nonzero(ar)` It uses to count non zero elements in the array.
- `np.where(ar>5)` it gives the array elements greater tean 5.
- `ar.sum()` sum of the array.
- `ar.min()` min element of the array.
- `ar.max()` max elements of the array.
- Sum of two matrix = `matrix1 + matrix2`.
- Multiplication of two matrix = `matrix1 * matrix2`.
- `ar.ndim` it gives the dimention of the array.
- `ar.argmin()` it gives the min element index.
- `ar.argmax()` it gives the max element index.
- `ar.sum(axis=0)` find the sum column wise of a matrix.
- `ar.sum(axis=1)` find the sum row wise of a matrix.
- `ar.T` transpose the matrix.

Thankyou❤️
If you find the repo.. is helpful than drop a star⭐
