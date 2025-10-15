🧩 Day 7 – Modules & Practice

 📚 Topics Covered:
- What are Modules?  
- Importing Modules  
- `math` Module  
- `random` Module  
- `datetime` Module  
- Practice (HackerRank-style tasks)

📘 What is a Module?

 🔹 Importing Modules


### Types of Import:
1. **Import the whole module**
   ```python
   import math
   print(math.sqrt(16))
   ```
2. **Import a specific function**
   ```python
   from math import sqrt
   print(sqrt(25))
   ```
3. **Import with an alias name**
   ```python
   import math as m
   print(m.pi)
   ```

 🔹 The `math` Module

### Example:
```python
import math

num = 9
print("Square root:", math.sqrt(num))
print("Power:", math.pow(2, 4))
print("Value of π:", math.pi)
```

🔹 The `random` Module

### Example:
```python
import random

print("Random number:", random.randint(1, 100))
colors = ["red", "green", "blue"]
print("Random color:", random.choice(colors))
```

 🔹 The `datetime` Module

### Example:
```python
import datetime

now = datetime.datetime.now()
print("Current Date and Time:", now)
print("Formatted Date:", now.strftime("%d-%m-%Y"))
print("Formatted Time:", now.strftime("%H:%M:%S"))
```

 💻 Practice – HackerRank Style Tasks

🧠 Task 1: Square Root Using `math` Module
**Input:** 49  
**Output:** 7.0  
```python
import math
num = int(input())
print(math.sqrt(num))
```

🎲 Task 2: Random Number Generator
**Description:** Generate and print 5 random integers between 10 and 50.  
```python
import random
for i in range(5):
    print(random.randint(10, 50))
```

⏰ Task 3: Current Date and Time
**Description:** Print the current date and time in a readable format.  
```python
import datetime
now = datetime.datetime.now()
print("Today:", now.strftime("%A, %d %B %Y - %I:%M %p"))
```

 📅 Task 4: Days Until New Year
**Description:** Calculate how many days are left until next New Year.  
```python
import datetime

today = datetime.date.today()
new_year = datetime.date(today.year + 1, 1, 1)
days_left = (new_year - today).days

print("Days left until New Year:", days_left)
```
