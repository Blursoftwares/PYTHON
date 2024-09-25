# **Input and Output**

---

## **Objectives**
- **Introduction to Input**: How to get information from the user.
- **Introduction to Output**: How to show information to the user.
- **Using `input()` and `print()`**: The basic functions for input and output in Python.

---

## **Introduction to Input**

In Python, **input** is how we ask the user to give us information. We use the `input()` function to get this information. Whatever the user types, we can store it in a variable and use it in our program.

---

#### **Example: Getting input from the user**

```python
name = input("What is your name? ")
print("Hello, " + name + "!")
```
- Here, input() asks the user for their name.
- The program then greets the user by printing out "Hello, [name]!".

> [!note] Input always comes in as a string!
> Even if the user types a number, Python will treat it like text unless we convert it.

## Introduction to Output
Output is how we show information to the user. In Python, we use the `print()` function to display messages, numbers, or any other information.
For example;
```python
age = 10
print("I am", age, "years old!")
```
Here, `print()` displays a message along with the variable `age`.

> [!tip] You can print multiple things!
> Just separate them with commas like in the example above.

## Converting Input to Other Data Types
Since `input()` always gives us a string (text), we often need to change it to other types like numbers. To do this, we can use functions like `int()` for integers or `float()` for decimal numbers.
 Let's convert this string into an number
```python
age = int(input("How old are you? "))
print("Next year, you will be", age + 1, "years old!")
```
Here, `input()` gets the user’s age as a string, but `int()` converts it to a number so we can do math with it. Cool stuff right?



