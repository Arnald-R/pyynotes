---
title: Switch3
date: 2025-02-05
author: Your Name
cell_count: 8
score: 5
---

```python
#created at 20250125
```


```python
https://www.scientecheasy.com/2022/11/switch-statement-in-python.html/
```


```python
def a():
    return 'Apple'
def m():
    return 'Mango'
def o():
    return 'Orange'
def fruits(i):
    switcher = {
        1: a,
        2: m,
        3: o,
        4: lambda: 'Banana'
    }
    funct = switcher.get(i, lambda: 'Invalid')
    return funct()
print(fruits(3)) # Calling function.
print(fruits(0)) # Calling function.

```

    Orange
    Invalid



```python
# This program code will execute only in python 3.10 or above versions
lang = input('Which programming language do you want to learn? ')

match lang:
    case "JavaScript":
        print('You will be a web developer after learning JavaScript.')

    case "Python":
        print("You will be a Data Scientist after learning Python.")

    case "PHP":
        print("You will be a backend developer after learning PHP.")

    case "Solidity":
        print("You will be a Blockchain developer after learning Solidity.")

    case "Java":
        print("You will be a software developer after learning Java")
    case _:
        print("Language does not matter.")

```

    Which programming language do you want to learn?  Java


    You will be a software developer after learning Java



```python

```


```python

```


```python

```


```python

```


---
**Score: 5**