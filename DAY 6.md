🐍 Day 6 – File Handling


🔹 Opening a File 
**Syntax:**
```python
file = open("filename.txt", "mode")
```


🔹 Reading from a File
```python
file = open("sample.txt", "r")
content = file.read()
print(content)
file.close()
```

🔹 Writing to a File
```python
file = open("sample.txt", "w")
file.write("Hello, Python File Handling!")
file.close()
```

 🔹 Appending Data to a File
```python
file = open("sample.txt", "a")
file.write("\nAdding new text to the file.")
file.close()
```

 🔹 Using `with open()` – Best Practice
```python
with open("sample.txt", "r") as file:
    data = file.read()
    print(data)
```

 ✅ Example – Write and Read File
```python
# Writing data
with open("info.txt", "w") as file:
    file.write("Name: Ananya\nCourse: Python Programming")

# Reading data
with open("info.txt", "r") as file:
    print(file.read())
```
