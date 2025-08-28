# 🔠 Strings and String Methods

## 1. What are Strings❓
Strings are a **sequence of characters** enclosed in **quotes**: `' '`, `" "`, or `''' '''`.

### Types of Strings 🌀

- **Single-quoted Strings**
```python
my_string: str = 'Hello, World!'
print(my_string)
```

- **Double-quoted Strings**
```python
my_string: str = "Hello, World!"
print(my_string)
```
> ✅ Both single and double quotes produce the same result.

- **Triple-quoted Strings**
```python
my_string: str = '''Hello,
World!'''
print(my_string)
```
> ✅ Triple quotes can **span multiple lines.**

## 2. Escape Sequence Characters ⚡
Escape sequence characters are represented by a **backslash** `\`. They have a specific meaning in strings.

For example:
```python
print("Hello, \nTriomind!") # \n means new line
print("Hello, \tTriomind!") # \t means tab and adds space
```

## 3. Performing Different Actions On Strings 🔤
| Name          | Description                                           | Example               |
|---------------|------------------------------------------------------|---------------------|
| Concatenation | Joining 2 strings                                    | "Hello," + " World!" |
| Indexing      | Access characters using **position (index)**        | my_string[0]        |
| Slicing       | Extract a **part of a string**                      | my_string[1:5]      |
| Length        | Find the number of characters in a string           | len(my_string)      |
| Upper Case    | Convert all letters in a string to **uppercase**    | my_string.upper()   |
| Lower Case    | Convert all letters in a string to **lowercase**    | my_string.lower()   |
| Capitalize    | Convert the **first letter** of a string to uppercase | my_string.capitalize() |

