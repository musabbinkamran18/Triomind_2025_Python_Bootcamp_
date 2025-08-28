# 💯 Operators in Python

In Python, we perform **operations** on values, like adding, subtracting, or comparing.

- The **values** we operate on are called **operands** 💎.
- The **symbol** that performs the operation is called the **operator** ⚡.

**Example:**
```python
2 + 5
```

---

# Types of Operators

## 1. Arithmetic Operators ➕➖✖️➗

Arithmetic operators are used to perform **mathematical calculations**.

| Operator | Description                  | Example       |
|----------|------------------------------|---------------|
| `+`      | Addition                     | `2 + 3 = 5`   |
| `-`      | Subtraction                  | `5 - 2 = 3`   |
| `*`      | Multiplication               | `2 * 3 = 6`   |
| `/`      | Division                     | `6 / 3 = 2.0` |
| `%`      | Modulus (remainder)          | `5 % 2 = 1`   |
| `**`     | Exponent (power)             | `2 ** 3 = 8`  |
| `//`     | Floor division (quotient)    | `5 // 2 = 2`  |

### Example
```python
a = 1 + 4
print(a)  # 5
```

---

## 2. Assignment Operators 📝

Assignment operators are used to **store or update values** in variables.

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

### Example
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

---

## 3. Comparison Operators ⚖️

Comparison operators **compare two values** and return `True` ✅ or `False` ❌.

| Operator | Description | Example |
|----------|-------------|---------|
| `==` | Equal to | `5 == 5` → True |
| `!=` | Not equal to | `5 != 3` → True |
| `>` | Greater than | `5 > 3` → True |
| `<` | Less than | `5 < 3` → False |
| `>=` | Greater than or equal to | `5 >= 5` → True |
| `<=` | Less than or equal to | `5 <= 3` → False |

### Example
```python
x = 5
y = 3
print(x > y)   # True
print(x == y)  # False
```

---

## 4. Logical Operators 🤔

Logical operators **combine Boolean values**.

| Operator | Description | Example |
|----------|-------------|---------|
| `and` | True if both are True | `True and False → False` |
| `or` | True if at least one is True | `True or False → True` |
| `not` | Inverts the Boolean value | `not True → False` |

### Example
```python
x = True
y = False
print(x and y)  # False
print(x or y)   # True
print(not x)    # False
```

---

## 5. Identity Operators 🧩

Identity operators **check if two objects are the same** in memory.

| Operator | Description | Example |
|----------|-------------|---------|
| `is` | True if both are the same object | `x is y` |
| `is not` | True if both are not the same object | `x is not y` |

### Example
```python
a = [1,2,3]
b = a
c = [1,2,3]
print(a is b)     # True
print(a is c)     # False
print(a is not c) # True
```

---

## 6. Membership Operators 🔍

Membership operators **check if a value is in a sequence** like a list, string, or tuple.

| Operator | Description | Example |
|----------|-------------|---------|
| `in` | True if value is present | `'a' in 'apple' → True` |
| `not in` | True if value is not present | `'b' not in 'apple' → True` |

### Example
```python
text = 'apple'
print('a' in text)     # True
print('b' not in text) # True
```

---

## 📝 Key Takeaways

- Operators work on **operands** 💎.
- Most operators return a **value** or a **Boolean** ✅❌.
- Choose the operator based on the **type of operation** you want to perform 🎯.

