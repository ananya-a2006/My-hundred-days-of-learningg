🐍 Day 9 – Indexing & Slicing

```python
import numpy as np

# 1D Indexing
arr = np.array([10, 20, 30, 40, 50])
print("First element:", arr[0])
print("Last element:", arr[-1])
print("Third element:", arr[2])

# 2D Indexing
arr2 = np.array([
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
])
print(arr2[0, 0])
print(arr2[1, 2])
print(arr2[-1, 1])

# 1D Slicing
arr3 = np.array([5, 10, 15, 20, 25, 30, 35])
print(arr3[1:5])
print(arr3[:4])
print(arr3[3:])
print(arr3[::2])

# 2D Slicing
arr4 = np.array([
    [10, 20, 30],
    [40, 50, 60],
    [70, 80, 90],
    [100, 110, 120]
])
print(arr4[1:3])
print(arr4[:2, :2])
print(arr4[-2:, :])

# Reshape Example
arr5 = np.array([1, 2, 3, 4, 5, 6])
reshaped = arr5.reshape(2, 3)
print(reshaped)

# Flatten Array
arr6 = np.array([
    [1, 2, 3],
    [4, 5, 6]
])
flat = arr6.flatten()
print(flat)

# Reshape with -1
arr7 = np.array([10, 20, 30, 40, 50, 60, 70, 80])
reshaped2 = arr7.reshape(4, -1)
print(reshaped2)
