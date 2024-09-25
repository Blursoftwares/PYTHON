# **Basic Operations and Arithmetic**

---

## **Objectives**
- **Introduction to Operators**: Adding, subtracting, multiplying, and dividing numbers.
- **Using Operators in Python**: How we can do math with Python.
- **Order of Operations**: Understanding which operations come first.

---

### **Introduction to Operators**

In Python, we use operators to do math. These operators are special symbols that tell the computer what kind of math we want to do.

Here are the common math operators:
- **Addition (`+`)**: Adds two numbers.
- **Subtraction (`-`)**: Takes one number away from another.
- **Multiplication (`*`)**: Multiplies two numbers together.
- **Division (`/`)**: Divides one number by another.

---

#### **Example: Using Operators in Python**

```python
# Addition
result = 5 + 3
print(result)  # Output will be 8

# Subtraction
result = 10 - 4
print(result)  # Output will be 6

# Multiplication
result = 7 * 2
print(result)  # Output will be 14

# Division
result = 8 / 2
print(result)  # Output will be 4.0
```

## Order of Operations
Python follows rules to decide which operation to do first when there are many. This is called the Order of Operations.

The order is:

1. Parentheses (()): Do what's inside the parentheses first.
2. Exponents (**): Powers like 2² or 3³.
3. Multiplication (*) and Division (/): Do these next.
4. Addition (+) and Subtraction (-): Do these last.

> [!note] PEMDAS Rule!
> Remember the order by using this phrase: "Please Excuse My Dear Aunt Sally" (Parentheses, Exponents, Multiplication, Division, Addition, Subtraction).

Let,s look at htis simple example:
```python
result = (2 + 3) * 4
print(result)  # Output will be 20, because we do (2+3) first, then multiply by 4.
```

