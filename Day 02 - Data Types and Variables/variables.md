# 🫙 Variables  

Think about your kitchen: your mom stores different spices in separate containers — one for sugar, another for salt, and so on.  

In Python, we also have **containers**, but instead of holding spices, they hold **data values**. These containers are called **variables**.  

👉 In simple words:  
A **variable** is like a box that stores a value, and you can change that value whenever you want.  

---

## 🔹 How to Create a Variable  
1. Open **Visual Studio Code**  
2. Create a new file (for example: `variables.py`)  
3. Type this code:  
   ```python
   var = "Hello, World!"
   print(var)
## 🔎 What Happened Here?
Python created a **variable** called `var`.

The value **"Hello, World!"** was stored inside `var`.

When we use `print(var)`, Python goes to the box named `var`, takes out the value, and shows it on the screen and thats how we can create a variable and print it

## Variable Naming Rules
When creating variables in Python, you must follow these rules:  

1. ✅ A variable name must **start with a letter or underscore (`_`)**  
   - Example: `name`, `_value`  

2. ✅ The rest of the name can contain **letters, numbers, or underscores**  
   - Example: `user1`, `total_amount`, `my_variable`  

3. ❌ A variable name **cannot start with a number**  
   - Invalid: `1value`  

4. ✅ Variable names are **case-sensitive**  
   - Example: `age` and `Age` are two different variables  

5. ❌ Variable names **cannot contain spaces**  
   - Invalid: `my variable`  
   - Valid: `my_variable`  

6. ❌ You **cannot use Python keywords** (like `for`, `while`, `class`, etc.) as variable names  

---

### ✅ Examples of Valid Variable Names  
```python
name = "Alice"
user_age = 25
total1 = 100
_value = "secret"
```

# 📖 Summary  

**Variables** are like **containers** that store **data values**.  

You create variables in Python using the **`=`** sign:  

```python
x = 10
name = "Alice"
```
### 📝 Variable Naming Rules

- Must start with a letter or underscore (_)

- Can contain letters, numbers, and underscores

- Cannot start with a number

- Cannot contain spaces

- Are case-sensitive (age and Age are different)

- Cannot use Python reserved keywords (like for, while, class)
