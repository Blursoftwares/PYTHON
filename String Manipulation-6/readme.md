# **String Manipulation**

---

## **Objectives**
- **Working with Strings**: Learn how to handle text in Python.
  - **Joining Strings**: How to combine text together.
  - **Splitting Strings**: How to break text into smaller parts.
  - **Slicing Strings**: How to get a part of a string.
  - **Changing Case**: Converting text to uppercase or lowercase.

---

## Working with Strings

A **string** is simply text, like a word or a sentence. In Python, strings are very powerful, and we can do lots of things with them! Let’s learn how to join, split, slice, and change the case of strings.

---

### **Joining Strings**

We can combine multiple strings into one. This is called **joining strings**. You can use the **`+`** operator to join two or more strings together.

#### **Example: Joining strings**

```python
first_name = "John"
last_name = "Doe"

full_name = first_name + " " + last_name
print("Full name:", full_name)
```
- Here, we combine the `first_name` and `last_name` variables into one string using the `+` operator.

> [!IMPORTANT]
> Don’t forget spaces!
> When joining strings, make sure to add spaces if you want them between the words.

---
### Splitting Strings
Sometimes, we want to break a string into smaller parts. This is called splitting a string. We can use the `split()` method to do this.
Let's look at the example below;

```python
sentence = "I love Python"
words = sentence.split()

print("Words:", words)
```
Here, the `split()` method breaks the sentence into a list of words.

### Slicing Strings
Slicing allows us to get a part of a string. You can think of it like cutting out a piece of text.

Example:
```python
greeting = "Hello, world!"
slice = greeting[0:5]  # Get the first 5 characters

print("Slice:", slice)
```
Here, we use slicing to get the first five characters of the string `"Hello, world!"`.

> [!NOTE]
> Slicing uses index numbers
> In Python, we start counting characters at `0`. The slice `[0:5]` means "get characters from position 0 up to (but not including) position 5."

## Changing Case
We can change all the letters in a string to uppercase (big letters) or lowercase (small letters). We do this using the `upper()` and `lower()` methods.
This is how we do it;
```python
text = "Python is fun!"

upper_text = text.upper()
lower_text = text.lower()

print("Uppercase:", upper_text)
print("Lowercase:", lower_text)
```

Here, we change the `text` to all uppercase and all lowercase.
