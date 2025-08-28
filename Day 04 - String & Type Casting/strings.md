# 🔠 Strings and String Methods

## 1. What are Strings❓
Strings are a **sequence of characters** enclosed in quotes: `' '`, `" "`, or `''' '''`.

### Types of Strings 🌀
- **Single-quoted Strings**
```python
my_string = 'Hello, World!'
print(my_string)
```
- **Double-quoted Strings**
```python
my_string = "Hello, World!"
print(my_string)
```
> ✅ Both single and double quotes are identical.
- **Triple-quoted Strings**
```python
my_string = '''Hello,
World!'''
print(my_string)
```
> ✅ Triple quotes can span **multiple lines**.

---

## 2. Escape Sequence Characters ⚡
Escape sequences use a **backslash `\`** to represent special characters.

| Escape Sequence | Meaning             | Example                        |
|-----------------|-------------------|--------------------------------|
| `\n`            | New line          | `"Hello\nWorld"`             |
| `\t`            | Tab / horizontal space | `"Hello\tWorld"`          |
| `\\`           | Backslash         | `"This is a backslash: \\"` |
| `\'`            | Single quote      | `'It\'s fine'`                 |
| `\"`           | Double quote      | `"He said, \"Hi!\""`       |

**Example:**
```python
print("Hello,\nTriomind!")  # New line
print("Hello,\tTriomind!")  # Tab space
```

---

## 3. Common String Operations 🔤

| Action        | Description                                         | Example                  |
|---------------|---------------------------------------------------|--------------------------|
| Concatenation | Joining two strings                                | `"Hello," + " World!"`|
| Indexing      | Access a character by its position                | `my_string[0]`           |
| Slicing       | Extract a substring                                | `my_string[1:5]`         |
| Length        | Number of characters                               | `len(my_string)`         |
| Upper Case    | Convert all letters to uppercase                  | `my_string.upper()`      |
| Lower Case    | Convert all letters to lowercase                  | `my_string.lower()`      |
| Capitalize    | Capitalize first character                        | `my_string.capitalize()` |
| Strip         | Remove leading/trailing whitespace                | `my_string.strip()`      |
| Replace       | Replace a substring                                | `my_string.replace("a","b")` |
| Split         | Split string into a list                            | `my_string.split(",")` |
| Join          | Join list elements into a string                  | `",".join(list_of_strings)` |

---

## 4. Concatenation ➕
```python
str1 = "Hello,"
str2 = " World!"
print(str1 + str2)
```
> ✅ Only strings can be concatenated; use `str()` for numbers.

---

## 5. Indexing 🔢
```python
my_string = "Hello, World!"
print(my_string[0])  # H
print(my_string[-1]) # !
```
> ✅ Negative indexing starts from the **end**.

---

## 6. Slicing ✂️
```python
my_string = "Hello, World!"

# 1: from index 1 to end
print(my_string[1:])   # ello, World!

# :1 from start to index 1 (exclusive)
print(my_string[:1])   # H

# 1:5 from index 1 to 4
print(my_string[1:5])  # ello

# Using negative indices
print(my_string[-5:])  # orld!
print(my_string[:-1])  # Hello, World

# Using steps
print(my_string[::2])  # Hlo ol!
print(my_string[1:10:3]) # e,W
```
> ✅ `start:end` **includes start, excludes end**. Step defines character skips. Leaving start or end empty defaults to beginning or end respectively.

