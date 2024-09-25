# **Conditions and Comparisons**

---

## **Objectives**
- **Introduction to Conditions**: How programs can make decisions.
- **Using `if`, `elif`, and `else`**: Controlling the flow of a program.
- **Comparing Values**: Using comparison operators to check for equality, greater than, or less than.

---

### **Introduction to Conditions**

Sometimes, we want our programs to make decisions based on certain conditions. For example, "If it’s raining, take an umbrella." In Python, we can do this using conditions.

A condition is like a question that can be answered with **True** or **False**. If the condition is **True**, the program does one thing. If it’s **False**, the program does something else.

---

### **Using `if`, `elif`, and `else`**

In Python, we use `if`, `elif`, and `else` to check conditions:

- **`if`**: This checks the first condition.
- **`elif`**: This checks another condition if the first one was False.
- **`else`**: This happens if none of the conditions were True.

---

#### **Example: Making decisions with `if`, `elif`, and `else`**

```python
age = int(input("How old are you? "))

if age < 10:
    print("You're still a kid!")
elif age >= 10 and age < 18:
    print("You're a teenager!")
else:
    print("You're an adult!")
```
Here, the program asks for the user’s age and then prints different messages depending on whether the user is a kid, a teenager, or an adult.

## Comparing Values
To make decisions, we need to compare values. Python uses comparison operators for this:
- `==`: Checks if two values are equal.
- `!=`: Checks if two values are not equal.
- `>` : Checks if the first value is greater than the second.
- `<`: Checks if the first value is less than the second.
- `>=`: Checks if the first value is greater than or equal to the second.
- `<=`: Checks if the first value is less than or equal to the second.

Let's try comparing these numbers
 ```python
 number = int(input("Guess a number between 1 and 10: "))

if number == 5:
    print("You guessed it right!")
else:
    print("Try again!")
```
Here, the program checks if the number guessed by the user is equal to 5.

> [!tip] Use comparison operators to make decisions!
> We can use comparisons to decide what our program should do, like checking if someone is old enough to drive or if they guessed the correct number.
 
In the next module, we will learn about loops, which allow us to do things over and over again in our programs!