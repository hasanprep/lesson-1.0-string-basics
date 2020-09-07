![Imgur](https://i.imgur.com/m0Nxl3L.png)

# Lesson 1.0: String Basics

## Objectives:

- Create strings in Python.
- Use variables to represent strings.

---

## Creating Strings

**Strings** or **string literals** are a sequence or characters. They are usually used to represent human language, file names, web addresses, etc. Things that are non-numeric sequences of characters are usually strings, but it is possible for a sequence of numeric characters to be a string as well. Stings in Python are created with either single quotes (`' '`) or double quotes (`" "`). You will definitely see them both ways. Some people prefer to use single quotes as it is one less key stroke. Here are some examples of strings:

`'We are leaning Python'`
`"Python is the 3rd most popular programming language."`
`'a'`
`'main.py'`
`"https://www.google.com/"`
`'3.141592653589793238462643383279'`
`" "`

Notice how the examples above are a sequence of characters between either `' '` or `" "`. The first two examples are sentences. The third is a single character. The fourth example is a file name. The fifth is the URL to Google. And even though the sixth example may appear to be numeric, it is also a string. The final string example is just a space. Even though this may not seem like a character, Python recognizes it as a character. This is an example of what is known as **whitespace**. Whitespace will be covered more in the subsequent lessons. 

As mentioned previously, it does not matter if `' '` is used or `" "` are used. Python will interpret them the same way. In fact it does not affect the string between the two types of quotes mention. We can test two strings using the **equality operator** (`==`) to determine if the they are the same or equal. Type the following in the REPL:

```python
'Python' == "Python"
```

The interpreter will output `True`, because the strings are identical between the two different quotes. Now try to input the following in the REPL:

```python
'Python' == "python"
```

The interpreter will output `False`, because the first string has a capital `P` and the second string has a lowercase `p`. So even though both strings say 'Python', Python can determine that there is a difference.

---
## Variables
When you create an object such as a string in Python, it is stored somewhere on the memory. **Variables** give you a way to access the string so it can be used again. You can create variables that point to strings using the assignment operator `=`. Variables are created as follows:

```python
first_name = 'Bob'
```

You can now print the name 'Bob' using the variable instead of the string.

```python
first_name = 'Bob'
print(name)
```

Choosing variable names has limitations: 

| Limitation                                                   | Good                            | Bad             |
| ------------------------------------------------------------ | ------------------------------- | --------------- |
| Variables cannot begin with a number.                        | `name1`                         | `1name`         |
| Variables cannot have special characters <br />other than an underscore (`_`). | `first_name`-                   | `first-name`,   |
| Variables cannot have whitespace.                            | `favorite_food`, `favoriteFood` | `favorite food` |

In addition to the limitations above, variables cannot be named using one of the **reserve words** or **keywords** in Python. These words have a special meaning in Python. Here is a list of these words:

`and`,  `as`, `assert`, `async`,`await`, `break`, `class`, `continue`, `def`, `del`, `elif`, `else`, `except`,  `False`, `finally`, `for`, `from`, `global`, `if`, `import`, `in`, `is`, `lambda`,  `None`, `nonlocal`, `not`, `or`, `pass`, `raise`, `return`, `True`, `try`, `while`, `with`, `yield`

---


# Lab 1.0: String Basics

Write a program that describes AND prints five things about yourself using five variables using five `print()` functions.

Here is an example program:

```python
# Declare five variables that describe yourself.
name = 'My name is Simon Escalada-Mastick.'
degrees = 'I studied linguistics and mathematics in college.'
occupation = 'I am a data analyst and teacher at HPLS.'
city = 'I live in Tucson, Arizona.'
favorite_restaurant = 'My favorite restaurant in Tucson is Yoshimatsu.'

# Print the five variables.
print(name)
print(degrees)
print(occupation)
print(city)
print(favorite_restaurant)
```

Turn in the code file in Google Classroom and submit the assignment in repl.it as well for full credit.