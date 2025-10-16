 🔢 Day 8 – Introduction to NumPy

 📚 Topics Covered:
- Creating Arrays  
- Array Data Types (`dtype`)  
- Array Shape (`shape`)  
- Basic Examples  


 🔹 Creating NumPy Arrays

To use NumPy, first import it using:
```python
import numpy as np
```

You can create arrays using `np.array()`:

```python
import numpy as np

arr = np.array([1, 2, 3, 4, 5])
print(arr)
```

🧩 Example – 2D Array
```python
matrix = np.array([[1, 2, 3],
                   [4, 5, 6]])
print(matrix)
```

 🔹 Data Type (`dtype`)

```python
arr = np.array([1, 2, 3, 4])
print("Data type:", arr.dtype)
```

**Setting a data type:**
```python
arr_float = np.array([1, 2, 3], dtype=float)
print(arr_float)
```


🔹 Array Shape (`shape`)

```python
matrix = np.array([[1, 2, 3],
                   [4, 5, 6]])
print("Shape:", matrix.shape)
```

**Output:**
```
Shape: (2, 3)
```
→ This means the array has 2 rows and 3 columns.


💻 Practice Examples

 🧠 Example 1 – 1D Array
```python
import numpy as np
arr = np.array([10, 20, 30])
print("Array:", arr)
print("Type:", type(arr))
```

 💡 Example 2 – 2D Array and Shape
```python
matrix = np.array([[5, 10, 15], [20, 25, 30]])
print("Array:\n", matrix)
print("Shape:", matrix.shape)
```

 🧮 Example 3 – Changing Data Type
```python
arr = np.array([1, 2, 3])
arr_float = arr.astype(float)
print("Converted Array:", arr_float)
print("New dtype:", arr_float.dtype)
```
