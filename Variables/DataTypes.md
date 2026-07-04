<div align="center">

# 🔢 Data Types in Python

### Understand the Different Types of Data Python Can Store

Data types define the kind of value a variable can hold. Python automatically identifies the data type based on the assigned value.

</div>

---

# 📖 Theory

A **data type** specifies the type of data that a variable can store.

Every value in Python belongs to a particular data type.

Python is a **dynamically typed language**, which means you don't need to specify the data type explicitly. Python automatically determines it when a value is assigned.

Example:

```python
age = 25
```

Python automatically recognizes that **25** is an integer.

---

# ❓ Why Do We Need Data Types?

Data types help Python:

- Store data efficiently.
- Perform valid operations.
- Reduce programming errors.
- Manage memory effectively.
- Improve code readability.

---

# 🚀 Features

- No need to declare data types.
- Automatically detected by Python.
- Supports multiple built-in types.
- Easy type conversion.
- Dynamic typing.
- Supports mutable and immutable objects.

---

# 📚 Categories of Data Types

| Category | Data Types |
|----------|------------|
| Numeric | int, float, complex |
| Text | str |
| Boolean | bool |
| Sequence | list, tuple, range |
| Set | set, frozenset |
| Mapping | dict |
| Binary | bytes, bytearray, memoryview |
| Special | NoneType |

---

# 💻 Syntax

```python
variable = value
```

Example

```python
age = 25
name = "Alice"
salary = 55000.75
is_student = True
```

---

# 📝 Numeric Data Types

## Integer (int)

Stores whole numbers.

```python
age = 25

print(age)

print(type(age))
```

Output

```
25
<class 'int'>
```

---

## Float

Stores decimal numbers.

```python
price = 99.99

print(price)

print(type(price))
```

Output

```
99.99
<class 'float'>
```

---

## Complex

Stores complex numbers.

```python
number = 5 + 3j

print(number)

print(type(number))
```

Output

```
(5+3j)
<class 'complex'>
```

---

# 📝 String

Stores text.

```python
name = "Python"

print(name)

print(type(name))
```

Output

```
Python
<class 'str'>
```

---

# 📝 Boolean

Stores either True or False.

```python
result = True

print(result)

print(type(result))
```

Output

```
True
<class 'bool'>
```

---

# 📝 List

Ordered and mutable collection.

```python
numbers = [10,20,30]

print(numbers)

print(type(numbers))
```

Output

```
[10, 20, 30]
<class 'list'>
```

---

# 📝 Tuple

Ordered but immutable collection.

```python
colors = ("Red","Green","Blue")

print(colors)

print(type(colors))
```

Output

```
('Red', 'Green', 'Blue')
<class 'tuple'>
```

---

# 📝 Set

Unordered collection of unique values.

```python
fruits = {"Apple","Mango","Orange"}

print(fruits)

print(type(fruits))
```

Output

```
{'Apple', 'Mango', 'Orange'}
<class 'set'>
```

---

# 📝 Dictionary

Stores data in key-value pairs.

```python
student = {
    "name":"Rahul",
    "age":22
}

print(student)

print(type(student))
```

Output

```
{'name': 'Rahul', 'age': 22}
<class 'dict'>
```

---

# 📝 NoneType

Represents no value.

```python
data = None

print(data)

print(type(data))
```

Output

```
None
<class 'NoneType'>
```

---

# 📝 Using type()

The `type()` function returns the data type of a variable.

```python
x = 10

print(type(x))
```

Output

```
<class 'int'>
```

---

# 📝 Type Conversion

## Implicit Conversion

Python converts automatically.

```python
x = 10
y = 5.5

print(x + y)
```

Output

```
15.5
```

---

## Explicit Conversion

Programmer converts manually.

```python
age = "25"

print(int(age))
```

Output

```
25
```

---

# ⚠️ Common Mistakes

## ❌ Mixing String and Integer

Wrong

```python
age = "20"

print(age + 5)
```

Correct

```python
age = int("20")

print(age + 5)
```

---

## ❌ Forgetting Quotes

Wrong

```python
name = Python
```

Correct

```python
name = "Python"
```

---

## ❌ Wrong Boolean

Wrong

```python
value = true
```

Correct

```python
value = True
```

---

# 💡 Best Practices

- Use appropriate data types.
- Use `type()` while learning.
- Convert data before calculations.
- Choose meaningful variable names.
- Keep data consistent.

---

# 🎯 Interview Questions

### 1. What is a data type?

**Answer:** A data type defines the type of value a variable stores.

---

### 2. Is Python dynamically typed?

**Answer:** Yes.

---

### 3. Which function returns the data type?

**Answer:** `type()`

---

### 4. Difference between List and Tuple?

| List | Tuple |
|------|------|
| Mutable | Immutable |

---

### 5. Difference between Set and Dictionary?

- Set stores only values.
- Dictionary stores key-value pairs.

---

### 6. What is None?

**Answer:** Represents no value or null.

---

### 7. Which data type stores decimal values?

**Answer:** float

---

### 8. Which data type stores text?

**Answer:** str

---

### 9. Which data type stores True or False?

**Answer:** bool

---

### 10. Can Python change variable type automatically?

**Answer:** Yes.

---

# 📝 Practice Exercises

## Beginner

1. Create an integer variable.
2. Create a float variable.
3. Create a string variable.
4. Create a boolean variable.
5. Print the data type of each.

---

## Intermediate

6. Create a list of five numbers.
7. Create a tuple of colors.
8. Create a dictionary of student details.
9. Create a set of fruits.
10. Print their data types.

---

## Challenge

11. Convert string to integer.
12. Convert integer to float.
13. Convert list to tuple.
14. Convert tuple to list.
15. Create a mini program using all major data types.

---

# ✅ Summary

After completing this topic, you have learned:

- ✅ What data types are
- ✅ Numeric types
- ✅ String
- ✅ Boolean
- ✅ List
- ✅ Tuple
- ✅ Set
- ✅ Dictionary
- ✅ NoneType
- ✅ Type conversion
- ✅ type() function

---

# 📚 Additional Resources

- Python Official Documentation
- Python Built-in Data Types
- PEP 8 Style Guide

---

# ➡️ Next Topic

# ➕ Operators in Python

In the next chapter, you'll learn:

- Arithmetic Operators
- Assignment Operators
- Comparison Operators
- Logical Operators
- Identity Operators
- Membership Operators
- Bitwise Operators

---

<div align="center">

## 🎉 Congratulations!

You have successfully completed **Data Types in Python**.

⭐ If you found this helpful, don't forget to **Star** this repository.

**Happy Coding! 🐍**

Made with ❤️ by **MygoMinds**

</div>
