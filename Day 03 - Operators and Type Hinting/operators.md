# 💯 Operators in Python

In Python, we perform **operations** on values, like adding, subtracting, or comparing.

- The **values** we operate on are called **operands**.
- The **symbol** that performs the operation is called the **operator**.

**Example:**
```python
2 + 5
```

---

# Types of Operators

## 1. Arithmetic Operators ➕➖✖➗

Arithmetic operators are used to perform **mathematical operations** in Python.

| Operator | Description                  | Example       |
|----------|------------------------------|---------------|
| `+`      | Addition                     | `2 + 3 = 5`   |
| `-`      | Subtraction                  | `5 - 2 = 3`   |
| `*`      | Multiplication               | `2 * 3 = 6`   |
| `/`      | Division                     | `6 / 3 = 2.0` |
| `%`      | Modulus (remainder)          | `5 % 2 = 1`   |
| `**`     | Exponent (power)             | `2 ** 3 = 8`  |
| `//`     | Floor division (quotient)    | `5 // 2 = 2`  |

---

## Examples of Each Operator

### ➕ Addition
```python
a = 1 + 4
print(a)  # Output: 5
```

### ➖ Subtraction
```python
a = 4 - 1
print(a)  # Output: 3
```

### ✖ Multiplication
```python
a = 4 * 1
print(a)  # Output: 4
```

### ➗ Division
```python
a = 4 / 1
print(a)  # Output: 4.0
```

### % Modulus (Remainder)
```python
a = 5 % 2
print(a)  # Output: 1
```

### ** Exponentiation (Power)
```python
a = 3 ** 2
print(a)  # Output: 9
```

### // Floor Division (Quotient)
```python
a = 3 // 2
print(a)  # Output: 1
```

---

## ✅ Note

You can also perform these operations **directly in the print statement**, without storing them in variables:
```python
print(5 + 3)  # 8
print(5 - 3)  # 2
print(5 * 3)  # 15
print(5 / 3)  # 1.666...
print(5 % 3)  # 2
print(5 // 3) # 1
print(5 ** 3) # 125
```

## 2. Assignment Operators
**Assignment** is the process of storing a **value** in a variable using the `=` operator.
```python
x = 5
```
Here the value of `5` is **assigned** to **x**
## +=
```python
x = 5
x += 3    # Same as x = x + 3
print(x)  # Output: 8
```
## -=
```python
x = 5
x -= 2    # Same as x = x - 2
print(x)  # Output: 3
```
