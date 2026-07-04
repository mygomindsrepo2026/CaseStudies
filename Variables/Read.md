<div align="center">

# 📝 Variables in Python

### Learn How to Store and Manage Data Efficiently

Variables are one of the fundamental building blocks of Python. They allow you to store, update, and manipulate data throughout your program.

</div>

---

# 📖 Theory

A **variable** is a named memory location used to store data.

Instead of remembering values directly, we assign them to variables with meaningful names.

Think of a variable as a **container** that stores information which can be used later in the program.

### Real-World Example

Imagine a student registration form.

```
Student Name : John
Age          : 21
College      : ABC College
```

Here,

- Student Name
- Age
- College

are variables that store different values.

---

# ❓ Why Do We Need Variables?

Without variables:

```python
print("John")
print(21)
print("ABC College")
```

Later, if the student's name changes, you must edit every occurrence.

With variables:

```python
name = "John"
age = 21
college = "ABC College"

print(name)
print(age)
print(college)
```

Now changing one value updates the entire program.

---

# 🚀 Features of Variables

- Easy to store data
- Easy to update values
- Improve code readability
- Reuse data multiple times
- Reduce duplicate code
- Support different data types
- No declaration required
- Dynamically typed

---

# 💻 Variable Syntax

```python
variable_name = value
```

Example

```python
name = "Alice"
age = 20
salary = 35000.50
is_student = True
```

---

# 📌 Variable Naming Rules

### ✅ Allowed

```python
name = "John"

student_name = "David"

studentAge = 21

_age = 20

age2 = 25
```

---

### ❌ Not Allowed

```python
2age = 20
```

Variable names cannot start with numbers.

---

```python
student-name = "John"
```

Hyphen (-) is not allowed.

---

```python
class = "Python"
```

Keywords cannot be used as variable names.

---

```python
student name = "John"
```

Spaces are not allowed.

---

# 📚 Naming Conventions

### Snake Case (Recommended)

```python
student_name = "Alice"

employee_salary = 50000

mobile_number = "9876543210"
```

---

### Camel Case

```python
studentName = "Alice"

employeeSalary = 50000
```

---

### Pascal Case

```python
StudentName = "Alice"

EmployeeSalary = 50000
```

---

# 📝 Examples

## Example 1: Store Student Details

```python
name = "Rahul"
age = 22
city = "Hyderabad"

print(name)
print(age)
print(city)
```

### Output

```
Rahul
22
Hyderabad
```

---

## Example 2: Store Product Information

```python
product = "Laptop"
price = 65000
brand = "Dell"

print(product)
print(price)
print(brand)
```

### Output

```
Laptop
65000
Dell
```

---

## Example 3: Store Employee Details

```python
employee_name = "David"
salary = 45000
department = "IT"

print(employee_name)
print(salary)
print(department)
```

### Output

```
David
45000
IT
```

---

## Example 4: Update Variable Value

```python
age = 20

print(age)

age = 21

print(age)
```

### Output

```
20
21
```

---

## Example 5: Multiple Assignment

```python
x, y, z = 10, 20, 30

print(x)
print(y)
print(z)
```

### Output

```
10
20
30
```

---

## Example 6: Assign Same Value

```python
a = b = c = 100

print(a)
print(b)
print(c)
```

### Output

```
100
100
100
```

---

# ⚠️ Common Mistakes

## ❌ Using Number at Beginning

Wrong

```python
1name = "John"
```

Correct

```python
name1 = "John"
```

---

## ❌ Using Spaces

Wrong

```python
student name = "John"
```

Correct

```python
student_name = "John"
```

---

## ❌ Using Keyword

Wrong

```python
if = 20
```

Correct

```python
age = 20
```

---

## ❌ Confusing Uppercase and Lowercase

```python
name = "Alice"

Name = "Bob"

print(name)

print(Name)
```

Output

```
Alice
Bob
```

Python is **case-sensitive**.

---

# 💡 Best Practices

✔ Use meaningful variable names.

```python
student_name = "Rahul"
```

Instead of

```python
x = "Rahul"
```

---

✔ Use **snake_case** for variables.

```python
student_name
```

---

✔ Keep names short but meaningful.

---

✔ Avoid single-letter variable names unless used in loops.

---

✔ Never use Python keywords.

---

# 🎯 Interview Questions

### 1. What is a variable in Python?

**Answer:** A variable is a named memory location used to store data.

---

### 2. Does Python require variable declaration?

**Answer:** No. Python creates variables automatically when a value is assigned.

---

### 3. Is Python dynamically typed?

**Answer:** Yes.

---

### 4. Can a variable change its data type?

**Answer:** Yes.

Example

```python
x = 10

x = "Python"
```

---

### 5. Is Python case-sensitive?

**Answer:** Yes.

```python
name = "Alice"

Name = "Bob"
```

These are two different variables.

---

### 6. Which naming convention is recommended in Python?

**Answer:** Snake Case.

---

### 7. Can variable names start with an underscore?

**Answer:** Yes.

Example

```python
_name = "Python"
```

---

### 8. Can Python variables contain numbers?

**Answer:** Yes, but not as the first character.

Correct

```python
age1 = 20
```

Wrong

```python
1age = 20
```

---

### 9. Can keywords be used as variable names?

**Answer:** No.

---

### 10. What operator is used for variable assignment?

**Answer:** Assignment Operator (=)

---

# 📝 Practice Exercises

## Beginner

1. Store your name in a variable.
2. Store your age.
3. Store your city.
4. Print all variables.
5. Change the value of a variable.

---

## Intermediate

6. Store student details.
7. Store employee details.
8. Store product details.
9. Swap two variables.
10. Use multiple assignment.

---

## Challenge

11. Create variables for a bank account.

12. Store details of five students.

13. Create variables for a shopping bill.

14. Calculate total marks using variables.

15. Create a simple employee information program.

---

# ✅ Summary

After completing this topic, you have learned:

- ✅ What variables are
- ✅ Why variables are used
- ✅ Variable syntax
- ✅ Naming rules
- ✅ Naming conventions
- ✅ Multiple assignment
- ✅ Dynamic typing
- ✅ Best practices
- ✅ Common mistakes

---

# 📚 Additional Resources

- Python Official Documentation
- PEP 8 Style Guide
- Python Variable Naming Conventions

---

# ➡️ Next Topic

## 🔢 Data Types

In the next chapter, you'll learn about:

- Numeric Types
- Strings
- Boolean
- Lists
- Tuples
- Sets
- Dictionaries
- NoneType

Understanding data types is essential because every variable in Python stores a specific type of data.
👉 **Click Here:** [🔢 Data Types](https://github.com/mygomindsrepo2026/CaseStudies/blob/main/Variables/DataTypes.md)
---

<div align="center">

## 🎉 Congratulations!

You have successfully completed **Variables in Python**.

⭐ If you found this helpful, consider starring the repository.

**Happy Coding! 🐍**

Made with ❤️ by **MygoMinds**

</div>
