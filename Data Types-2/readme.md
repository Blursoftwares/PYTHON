# Common Data Types in Python
---
 ## Objectives
- Learn about the most common data types in Python.
- Compare Python data types to similar or equivalent types in JavaScript.

## Introduction
Python, like JavaScript, offers multiple built-in data types that we can use to represent various types of information in our apps. In this lesson, we'll look at the similarities and differences between how Python and JavaScript handle various data types.

Make sure to work through the examples in this lesson in Python shell! Python, as an object-oriented language, provides many capabilities for inspecting various data kinds, so you'll learn more by working with the code. Open the Python shell on your terminal by typing `python `or `python3`.

## 1. Strings (`str`)
A string is a sequence of characters used to represent text in Python. Strings are enclosed in single or double quotes.

```python
name = "Alice"
```

> [!NOTE]
> Strings in Python are immutable, meaning you can't change the characters once the string is created.

## 2. Integers (`int`)
An integer is a whole number, positive or negative, without a decimal point.
```python
age = 10
```
> [!important]
> In Python, there is no limit to how large an integer can be. It can grow as big as the available memory allows.

## 3. Floats (`float`)
A float is a number with a decimal point.
```python
height = 5.8
```
> [!tip] 
> Floats can sometimes behave unexpectedly due to how computers handle decimals, similar to JavaScript.

## 4. Booleans (`bool`)
A boolean can only have two values: `True` or `False`. It's used for conditions and logic.
```python
is_student = True
```
> [!NOTE]
> In Python, `True` and `False` are capitalized. In JavaScript, it's lowercase (`true`/`false`).

## 5. Lists (`list`)
A list in Python is an ordered collection of items, which can be of any data type.Just like arrays in JavaScript, lists are mutable, meaning their contents can be changed.
```python
fruits = ["apple", "banana", "cherry"]
```
> [!important]
> Lists in Python are dynamic and can grow or shrink in size, similar to arrays in JavaScript.

## 6. Tuples (`tuple`)
A tuple is like a list, but it's immutable, meaning you can't change its contents once it's created.
```python
coordinates = (10.0, 20.0)
```
> [!tip]
> Use tuples when you need to store data that shouldn't change.

## 7. Sets (`set`)
A set is an unordered collection of unique items. This means no duplicates are allowed.
```python
colors = {"red", "green", "blue"}
```

> [!note]
> Since sets are unordered, you cannot access items by index like in lists.

## 8. Dictionaries (`dict`)
A dictionary is a collection of key-value pairs.Just like an object in JavaScript, each key is associated with a value, and both the key and value can be any data type.
```python
student = {"name": "Alice", "age": 10}
```
## 9. None (`None`)
In Python, `None` represents the absence of a value, similar to `null` or `undefined` in JavaScript.
```python
result = None
```

