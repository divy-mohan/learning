# 🖨️ Python `print()` Function (Hinglish Notes)

## `print()` Kya Hota Hai?

`print()` ek **built-in function** hai jo screen par output dikhata hai.

Example:

``` python
print("Hello World")
```

Output:

    Hello World

------------------------------------------------------------------------

# 1. Direct Print

## Syntax

``` python
print(variable, variable2, "Statement")
```

### Example

``` python
name = "Ram"
age = 20

print(name, age, "is a student")
```

### Output

    Ram 20 is a student

## Step by Step

### `print(`

Python ko bolte hain:

> "Jo bhi andar diya hai, usko screen par dikhao."

### `name`

``` python
name = "Ram"
```

Memory:

    name
     │
     ▼
    "Ram"

Python variable ka **naam** nahi, uski **value** print karta hai.

Output:

    Ram

------------------------------------------------------------------------

### `age`

``` python
age = 20
```

Memory:

    age
     │
     ▼
    20

Output:

    20

------------------------------------------------------------------------

### `"is a student"`

Ye ek **String Literal** hai.

Python ise exactly waise hi print karega.

------------------------------------------------------------------------

### Comma `,`

Comma ka matlab:

> "Next value bhi print karo."

Python automatically comma ke baad **ek space** add karta hai.

Example:

``` python
print("Ram", 20)
```

Output:

    Ram 20

------------------------------------------------------------------------

## Multiple Variables

``` python
city = "Delhi"
country = "India"

print(city, country)
```

Output:

    Delhi India

------------------------------------------------------------------------

## Different Data Types

``` python
name = "Ram"
age = 20
height = 5.8
student = True

print(name, age, height, student)
```

Output:

    Ram 20 5.8 True

------------------------------------------------------------------------

# Memory Diagram

    RAM Memory

    name ─────► "Ram"
    age  ─────► 20
    height ───► 5.8
    student ──► True

Python print karta hai:

    Ram 20 5.8 True

------------------------------------------------------------------------

# 2. Format Print (f-string)

## Syntax

``` python
print(f"Statement {variable}")
```

Example:

``` python
name = "Ram"

print(f"My name is {name}")
```

Output:

    My name is Ram

------------------------------------------------------------------------

## `f` Ka Matlab

`f` ka matlab hai **Formatted String**.

Python ko bolte ho:

> "Is string ke andar variables ko replace kar dena."

Agar `f` nahi likhoge:

``` python
print("My name is {name}")
```

Output:

    My name is {name}

Agar `f` likhoge:

``` python
print(f"My name is {name}")
```

Output:

    My name is Ram

------------------------------------------------------------------------

## Curly Braces `{}`

Curly braces ke andar variable likhte hain.

``` python
{name}
```

Python us variable ki value insert kar deta hai.

------------------------------------------------------------------------

## Multiple Variables

``` python
name = "Ram"
age = 20

print(f"My name is {name} and I am {age} years old.")
```

Output:

    My name is Ram and I am 20 years old.

------------------------------------------------------------------------

## Calculation bhi Kar Sakte Ho

``` python
a = 10
b = 20

print(f"Sum = {a + b}")
```

Output:

    Sum = 30

------------------------------------------------------------------------

# Direct Print vs Format Print

  -----------------------------------------------------------------------
  Direct Print                        Format Print
  ----------------------------------- -----------------------------------
  `print(name, age)`                  `print(f"{name} {age}")`

  Jaldi values dikhane ke liye.       Beautiful sentence banane ke liye.

  Python khud space add karta hai.    Space aur formatting tum control
                                      karte ho.

  Debugging ke liye useful.           Professional output ke liye best.
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# Easy Trick

### Direct Print

    Ram    20

Sirf values print hoti hain.

### Format Print

Template:

    "My name is ____ and my age is ____."

Python blanks fill karta hai:

    My name is Ram and my age is 20.

------------------------------------------------------------------------

# Remember

-   `print(variable1, variable2)` → Simple output.
-   `print(f"...{variable}...")` → Professional aur readable output.
