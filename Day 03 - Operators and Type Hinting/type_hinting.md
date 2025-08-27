# 🌀 Type Hinting

Imagine sharing your code with a beginner who wants to **know the type of a variable**.  
You can **hint the variable type** using type hinting.

---

## How to Type Hint ❓

```python
a: int
```
- After writing the variable name, add a **colon** `:` and then the **type** of the variable, as shown above.

- This helps others (and tools) understand what kind of value the variable should hold.

## What Happens When We Write It Wrong 🛠️

If we **write a wrong type** in Python, it **will not generate an error** by default.  
Python will still run the code, because **type hints are just suggestions**, not strict rules.  

**Example:**
```python
a: int = "Hello"  # Type hint says int, but value is a string
print(a)
```
✅**Output:**
```ngnix
Hello
```
