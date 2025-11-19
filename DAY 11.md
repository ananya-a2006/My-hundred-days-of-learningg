 🐍 Day 11 – Math & Random (Programs Only)

```python
# Program 1: Mean of an array
import numpy as np

arr = np.array([10, 20, 30, 40])
print("Mean:", np.mean(arr))

# Program 2: Standard deviation
import numpy as np

arr = np.array([10, 20, 30, 40])
print("Standard Deviation:", np.std(arr))

# Program 3: Random integer between 1 and 10
import numpy as np

print("Random Integer:", np.random.randint(1, 10))

# Program 4: Array of 5 random numbers (0–1)
import numpy as np

print("Random Floats:", np.random.rand(5))

# Program 5: Random 2x3 matrix
import numpy as np

print("2x3 Random Matrix:\n", np.random.rand(2, 3))

# Program 6: Random numbers from normal distribution
import numpy as np

print("Normal Distribution:", np.random.randn(5))

# Program 7: Random choice from list
import numpy as np

items = ["apple", "banana", "cherry"]
print("Random Choice:", np.random.choice(items))

# Program 8: Shuffle an array
import numpy as np

arr = np.array([1, 2, 3, 4, 5])
np.random.shuffle(arr)
print("Shuffled Array:", arr)

# Program 9: Random integers array
import numpy as np

print("Random Integers:", np.random.randint(1, 100, size=5))

# Program 10: Mean & Std of random numbers
import numpy as np

data = np.random.randint(1, 50, size=10)
print("Data:", data)
print("Mean:", np.mean(data))
print("Std Dev:", np.std(data))
