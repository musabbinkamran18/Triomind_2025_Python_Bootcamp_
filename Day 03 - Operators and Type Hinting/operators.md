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

## 2. Assignment Operators

**Assignment** is the process of storing a **value** in a variable using the `=` operator.
```python
x = 5
```
Here, the value `5` is **assigned** to the variable `x`.

| Operator | Description | Example |
|----------|-------------|---------|
| `=` | Assign a value to a variable | `x = 5` |
| `+=` | Add to variable and assign | `x += 3` → `x = x + 3` |
| `-=` | Subtract from variable and assign | `x -= 2` → `x = x - 2` |
| `*=` | Multiply variable and assign | `x *= 2` → `x = x * 2` |
| `/=` | Divide variable and assign | `x /= 2` → `x = x / 2` |
| `//=` | Floor divide variable and assign | `x //= 3` → `x = x // 3` |
| `%=` | Modulus variable and assign | `x %= 3` → `x = x % 3` |
| `**=` | Exponent variable and assign | `x **= 3` → `x = x ** 3` |

### Examples:
```python
x = 5
x += 3
print(x)  # 8
x -= 2
print(x)  # 6
x *= 2
print(x)  # 12
x /= 3
print(x)  # 4.0
x //= 3
print(x)  # 1.0
x %= 2
print(x)  # 1.0
x **= 3
print(x)  # 1.0
```
## 3. Comparision Operators
**Comparison operators** are used to **compare two values**.
## Note:
- They check a condition and return a Boolean value `True` or `False`.
