# 🐍 Day 001 – Python Basics Unlocked

## 📅 Date
`2025-06-14`

## 📘 What I Learned

| Concept      | Description or Example                                                      |
|--------------|------------------------------------------------------------------------------|
| `print()`    | Display output in terminal. `print("Hello!")`                               |
| `input()`    | Get user input. `input("What's your name? ")`                               |
| `len()`      | Returns the number of characters in a string. `len("Bhimo") → 5`            |
| Comments     | Use `#` to leave notes in code                                               |
| Variables    | Store values like `name = "Bhimo"`                                          |
| Debugging    | Fixing syntax or logic errors                                               |

## 🧠 Key Takeaways

- Python is very beginner-friendly and reads like English.
- `input()` and `print()` make interaction fun even on day one.
- `len()` is a handy function for basic string inspection or validation.

## 🔧 Code Snippets / Examples

```python
# Basic interaction
print("Hello, world!")
name = input("What's your name?\n")
print("Nice to meet you, " + name)

# Using len()
print(len(name))  # prints the number of characters in the user's name
````

## 🎯 Daily Challenge / Project

> **Band Name Generator** – Ask the user for the name of the city they grew up in and their pet’s name, then combine the two into a potential band name.

```python
print("Welcome to the Band Name Generator.")
city = input("What's the name of the city you grew up in?\n")
pet_name = input("What's your pet's name?\n")
print("Your band name could be " + city + " " + pet_name)
```

## 🔍 Reflections

* **What I struggled with**: remembering the proper way to nest `input()` into `print()`, and small syntax typos.
* **What I enjoyed**: seeing the program interact back — especially in the mini challenge!
* **What I want to explore more**: string formatting using f-strings and combining multiple inputs more dynamically.

## 🔗 Resources

* [Angela Yu's 100 Days of Code Python Bootcamp](https://www.udemy.com/course/100-days-of-code/)
* [Official Python Documentation – Built-in Functions](https://docs.python.org/3/library/functions.html)

