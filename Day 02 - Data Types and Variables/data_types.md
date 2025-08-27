# 📊 Data Types  

## What are Data Types?  
**Data Types** define the kind of value a variable can hold.  
For example, whether the value is an **integer number**, a **list of items**, or some **text**.  

---

# 📊 General Data Types 

- **Integer / Float** 🔢 🌊 → `x = 42`, `pi = 3.14`  
- **String (Text)** 🔤 📝 ✍️ → `name = "Alice"`  
- **Boolean (True/False)** ✅ ❌ 🔒🔓 → `is_active = True`  
- **List / Array** 📋 🗂️ → `fruits = ["apple", "banana"]`  
- **Tuple (Fixed List)** 📦 → `point = (3, 4)`  
- **Dictionary / Map** 📖 🗝️📦 → `user = {"name": "Bob"}`  
- **Set (Unique Items)** 🧩 🌀 → `unique = {1, 2, 3}`  

---
## 🔢 1. Integer (`int`)  
This data type is used for **whole numbers** (positive or negative).  

**Example:**  
```python
a: int = 12
print(a)
```

---

## 🌊 2. Floating-Point (`float`)  
This data type is used for **decimal numbers**.  

**Example:**  
```python
a: float = 1.2
print(a)
```

---

## 🔤 3. String (`str`)  
This data type allows us to store **a sequence of characters** inside quotes (`" "`, `' '`, or `''' '''`).

**Example:**  
```python
a: str = "Hello, World!"
print(a)
```

---

## ✅ ❌ 4. Boolean (`bool`)  
This data type represents **True or False** values.  
For example: `5 > 2 -> True` because 5 is greater than 2.

**Example:**  
```python
a: bool = True
print(a)
```

---

## 📋 5. List (`list`)  
This data type is a **collection of ordered data items** that can be changed (mutable).  

**Example:**  
```python
a: list = ["Hello, World!", 12, 1.2]
print(a)
```

**Note:**  
Lists can contain **any type of data** and always start with **square brackets `[ ]`**.

---

## 📦 6. Tuple (`tuple`)  
This data type is similar to a list, **but it is immutable**, meaning its values cannot be changed after creation.  

**Example:**  
```python
a: tuple = ("Hello, World!", 12, 1.2)
print(a)
```

---

## 📖 7. Dictionary (`dict`)  
A **dictionary** is a **collection of key-value pairs**, where each key is **unique** and used to store and retrieve values efficiently.  

**Example:**  
```python
a: dict = {"chocolate": 13, "eggs": 25, "milk": 125}
print(a)
```

---

## 🧩 8. Set (`set`)  
A **set** is a **collection of unique items**, unordered and without duplicates.  

**Example:**  
```python
a: set = {1, 2, 11, 3}
print(a)
```

## 📊 Summary of Python Data Types
- **Integer (`int`)** 🔢 → Whole numbers (positive or negative)
- **Floating-Point (`float`)** 🌊 → Decimal numbers
- **String (`str`)** 🔤 → Sequence of characters
- **Boolean (`bool`)** ✅❌ → True or False values
- **List (`list`)** 📋 → Ordered, mutable collection of items
- **Tuple (`tuple`)** 📦 → Ordered, immutable collection of items
- **Dictionary (`dict`)** 📖 → Collection of unique key-value pairs
- **Set (`set`)** 🧩 → Unordered collection of unique items
