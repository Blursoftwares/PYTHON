# **Python Loops**

---

## **Objectives**
- **What are loops?**: Understanding how loops help us repeat actions.
- **Types of loops in Python**: Exploring the two main types: `for` and `while` loops.
- **Where do we use loops?**: Learning when and why loops are helpful in programming.

---

### **What are Loops?**

A **loop** is a way to make the computer do the same thing over and over again. Instead of writing the same code many times, we can use a loop to repeat actions. 

For example, if you want to say "Hello" 5 times, you don’t have to write `print("Hello")` 5 times. You can use a loop to do it for you!

---

### **Types of Loops in Python**

There are two main types of loops in Python:

- **`for` loops**: These loops repeat a block of code for a specific number of times or over a list of things.
- **`while` loops**: These loops keep repeating as long as a certain condition is True.

---

#### **1. `for` Loops**

A **`for` loop** goes through a list or a range of numbers and repeats the same action for each one.

#### **Example: `for` loop**

```python
# Repeat "Hello!" 5 times
for i in range(5):
    print("Hello!")
```

This for loop prints `"Hello!"` 5 times. The `range(5)` creates a list of numbers from 0 to 4, and the loop runs 5 times, once for each number.
> [!NOTE]
> `range()` starts from 0!
> he function `range(5)` creates a list like this: `[0, 1, 2, 3, 4]`.

## While loop

A `while` loop keeps going as long as something is True. It’s useful when you don’t know how many times you need to repeat an action. For this example,
we will give the user infinite chances to guess your lucky number:

```python
# Keep asking for a number until the user gives 5
number = 0

while number != 5:
    number = int(input("Guess the number (1 to 10): "))

print("You guessed it right!")
```
This `while` loop keeps asking the user to guess a number until they guess 5.

> [!tip]
> Be careful with `while` loops!
> If the condition in a while loop is always True, it will never stop, and the loop will run forever.

## Where Do We Use Loops?
Loops are helpful when:

- We need to repeat an action multiple times.
- We want to go through a list of items one by one (like printing all the names in a list).
- We want to keep asking a question until we get the right answer.

Let's look at a second example, that prints the fruits in our array;
```python
# Print each fruit in the list
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```
This `for` loop goes through each item in the list `fruits` and prints it.

> [!important] 
> Use loops to avoid repeating code!
> Loops make your code cleaner and easier to manage, especially when you need to do the same thing many times.



