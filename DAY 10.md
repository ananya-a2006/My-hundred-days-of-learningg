 🐍 Day 10 – Array Operations 

```python
# Program 1: Broadcasting – Add scalar to array
import numpy as np

arr = np.array([10, 20, 30])
print("Scalar Added:", arr + 5)



# Program 2: Broadcasting – Add row vector to matrix
import numpy as np

matrix = np.array([[1, 2, 3],
                   [4, 5, 6]])

row = np.array([1, 1, 1])

print("Matrix + Row:\n", matrix + row)



# Program 3: Broadcasting – Multiply column vector
import numpy as np

matrix = np.array([[5, 10, 15],
                   [20, 25, 30]])

col = np.array([[2],
                [2]])

print("Matrix * Column:\n", matrix * col)



# Program 4: Vectorized Addition
import numpy as np

a = np.array([1, 2, 3])
b = np.array([4, 5, 6])

print("Added:", a + b)


# Program 5: Vectorized Multiplication
import numpy as np

arr = np.array([2, 4, 6, 8])
print("Multiplied:", arr * 3)



# Program 6: Vectorized Math (sqrt, log, exp)
import numpy as np

arr = np.array([1, 4, 9, 16])

print("sqrt:", np.sqrt(arr))
print("log:", np.log(arr))
print("exp:", np.exp(arr))



# Program 7: Vectorized Trigonometry
import numpy as np

angles = np.array([0, np.pi/2, np.pi])

print("sin:", np.sin(angles))
print("cos:", np.cos(angles))
print("tan:", np.tan(angles))



# Program 8: Vectorized Comparison
import numpy as np

arr = np.array([10, 20, 30, 40])

print("Greater than 25:", arr > 25)
print("Equals 20:", arr == 20)



# Program 9: Vectorized Scaling (ML Feature Scaling)
import numpy as np

data = np.array([50, 100, 150])
print("Scaled:", data / 100)



# Program 10: Power Operation (Element-wise)
import numpy as np

arr = np.array([1, 2, 3, 4])
print("Squared:", arr ** 2)



