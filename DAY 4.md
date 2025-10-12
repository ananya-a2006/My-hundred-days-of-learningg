 🐍 Day 4 – Conditionals & Loops

Topics Covered:
- Conditional Statements (`if`, `elif`, `else`)  
- `for` Loops  
- `while` Loops  
- Loop Control Statements (`break`, `continue`)  
- Practice Programs  


⚖️ 1. Conditional Statements (if–elif–else)


```python
# Example of if-elif-else
age = int(input("Enter your age: "))

if age < 18:
    print("You are a minor.")
elif age == 18:
    print("You just became an adult!")
else:
    print("You are an adult.")
```

💡 Nested `if` Example

```python
marks = int(input("Enter your marks: "))

if marks >= 50:
    if marks >= 90:
        print("Excellent!")
    else:
        print("You passed!")
else:
    print("Better luck next time.")
```

 🔁 2. Loops in Python

🔸 `for` Loop

```python
# for loop example
for i in range(1, 6):
    print("Number:", i)
```

💬 Example – Iterating Over a List

```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print("I like", fruit)
```

🔹 `while` Loop

```python
# while loop example
count = 1
while count <= 5:
    print("Count =", count)
    count += 1
```

💻 Example

```python
# break and continue example
for num in range(1, 10):
    if num == 5:
        continue   # skip number 5
    if num == 8:
        break      # stop loop at 8
    print(num)
```

**Output:**
```
1
2
3
4
6
7
```

🧩 Practice Program 1 – Check Even or Odd

```python
# Program to check if number is even or odd
num = int(input("Enter a number: "))

if num % 2 == 0:
    print(num, "is Even")
else:
    print(num, "is Odd")
```

💻 Practice Program 2 – Sum of First N Numbers (for loop)

```python
n = int(input("Enter a number: "))
total = 0

for i in range(1, n + 1):
    total += i

print("Sum of first", n, "numbers is:", total)
```

🔄 Practice Program 3 – Multiplication Table (while loop)

```python
num = int(input("Enter a number: "))
i = 1

while i <= 10:
    print(num, "x", i, "=", num * i)
    i += 1
```

💡 Practice Program 4 – Positive, Negative or Zero

```python
num = float(input("Enter a number: "))

if num > 0:
    print("Positive")
elif num == 0:
    print("Zero")
else:
    print("Negative")
```
