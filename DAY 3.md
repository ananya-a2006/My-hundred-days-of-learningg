 🐍 Day 3 – Tuples, Sets & Dictionaries

 Topics Covered:
- Tuples – Definition & Immutability  
- Sets – Unique Elements & Operations  
- Dictionaries – Key–Value Pairs  
- Practice Programs  


🎯 1. Tuples

```python
# Tuple example
fruits = ("apple", "banana", "cherry")
print(fruits)
print("First fruit:", fruits[0])
```

### 📘 Tuple Example

```python
# Tuple operations
numbers = (10, 20, 30, 40, 20)

print("Tuple:", numbers)
print("Count of 20:", numbers.count(20))
print("Index of 30:", numbers.index(30))

# Trying to modify tuple will cause an error
# numbers[0] = 99  ❌ TypeError
```

 🧩 2. Sets

```python
# Set example
numbers = {1, 2, 3, 4, 4, 5}
print("Set:", numbers)  # duplicates removed
```


💻 Set Example

```python
# Set operations
A = {1, 2, 3, 4}
B = {3, 4, 5, 6}

print("A union B:", A.union(B))
print("A intersection B:", A.intersection(B))
print("A difference B:", A.difference(B))

A.add(10)
print("After adding 10:", A)
A.remove(2)
print("After removing 2:", A)
```

🗝️ 3. Dictionaries

```python
# Dictionary example
student = {"name": "Ananya", "age": 18, "course": "Python"}

print("Dictionary:", student)
print("Name:", student["name"])
print("Age:", student["age"])

💻 Dictionary Example

```python
# Dictionary operations
student = {"name": "Ananya", "age": 18, "course": "Python"}

print("Keys:", student.keys())
print("Values:", student.values())
print("Items:", student.items())

student["grade"] = "A+"  # adding new key
print("Updated:", student)

student.pop("age")  # removing a key
print("After removing age:", student)

# Looping through dictionary
for key, value in student.items():
    print(key, ":", value)
```


 🧠 Practice Program 1 – Tuple & Set

```python
# Tuple and Set Practice

numbers = (1, 2, 3, 4, 5, 3, 2)
print("Original Tuple:", numbers)

# Convert to set to remove duplicates
unique = set(numbers)
print("Unique values:", unique)

# Convert back to tuple
unique_tuple = tuple(unique)
print("Converted back to tuple:", unique_tuple)
```

💻 Practice Program 2 – Dictionary Tasks

```python
# Dictionary Practice

student = {
    "name": input("Enter student name: "),
    "age": int(input("Enter age: ")),
    "course": input("Enter course: ")
}

print("\n--- Student Details ---")
for key, value in student.items():
    print(key.capitalize(), ":", value)

# Add a new key and update
student["grade"] = input("Enter grade: ")
print("\nUpdated Record:", student)
```
