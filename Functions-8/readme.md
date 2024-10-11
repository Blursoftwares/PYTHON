# **Python Functions**

---

## **Objectives**
- **What are functions?**: Learn how to create reusable blocks of code.
- **Creating a function**: Understand how to define and call functions in Python.
- **Parameters and arguments**: Learn how to pass information to functions.
- **Return values**: Get information back from a function.

---

## **What are Functions?**

A **function** is like a little machine that we can use to do something for us. We give it a name and some instructions, and whenever we call the function, it runs those instructions.

Think of a function as a box. You put some information in the box, it does something, and then you can get a result back.

Functions help us:
- Avoid writing the same code over and over.
- Break a big task into smaller parts.

---

## **Creating a Function**

To create a function, we use the **`def`** keyword, followed by the function name and some parentheses `()`.

#### **Example: Defining and Calling a Function**

```python
def say_hello():
    print("Hello, world!")

# Call the function
say_hello()
```
In this example, we define a function called `say_hello()`. Inside the function, it prints "Hello, world!" when we call it.
> [!NOTE]
> Defining vs. Calling a Function
> Defining a function gives it a name and some instructions, but it won't run until we call it using its name.

## Parameters and Arguments
Functions can take parameters, which are pieces of information that we pass into the function so it can work with them.
Take a lppk at this example:
```python
def greet(name):
    print("Hello, " + name + "!")

# Call the function with an argument
greet("Alice")
```
The `greet() `function takes one parameter, `name`. When we call the function and give it a name (like "Alice"), it prints a greeting using that name.

> [!IMPORTANT]
> Parameters vs. Arguments
> - Parameters are the placeholders inside the function definition.
> - Arguments are the actual values we pass when calling the function.

## Return values
Sometimes, we want a function to give us a result. We use the `return` keyword to send something back from the function.
Example:
```python
def add_numbers(a, b):
    return a + b

# Call the function and store the result
result = add_numbers(5, 3)
print(result)
```
In this example, the function `add_numbers()` takes two parameters (`a` and `b`) and returns their sum. The result is then stored in the `result` variable and printed.

> [!TIP]
> Use return to Get Results!
> Functions that return values allow you to save the result and use it later in your code.

## Where Do We Use Functions?
Functions are useful when:

- We need to do the same task multiple times.
- We want to organize our code and break big tasks into smaller, reusable parts.