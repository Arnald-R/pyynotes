---
title: Escape Sequence
date: 2025-02-05
author: Your Name
cell_count: 12
score: 10
---

```python
#createdat 20250120
```


```python
https://www.scientecheasy.com/2022/09/escape-sequence-in-python.html/
```


```python
print('He said 'Python is fun unlimited'')

```


      Cell In[3], line 1
        print('He said 'Python is fun unlimited'')
              ^
    SyntaxError: invalid syntax. Perhaps you forgot a comma?




```python
print("He said 'Python is fun unlimited'")

```

    He said 'Python is fun unlimited'



```python
# \’:
print('Good Morning \'Arnald\'')
```

    Good Morning 'Arnald'



```python
# \":
print("Welcome to \"Python class\"")

```

    Welcome to "Python class"



```python
# \t:
print("Welcome to\tNew home")

```

    Welcome to	New home



```python
# \n:
print("Good Morning \nScientech Easy")
print("*\n**\n***\n")

```

    Good Morning 
    Scientech Easy
    *
    **
    ***
    



```python
# \\: 
print('Good Evening \\Scientech Easy\\')
```

    Good Evening \Scientech Easy\



```python
# \r: This escape sequence moves the output \
# point back to the beginning of the line without moving down a line (generally).
print('Good Morning \rnew letter')
```

    new letterng 



```python
#important escape sequence characters:

print("1. Hello \'Python")
print("2. Hello \"Python")
print("3. Hello \tPython")
print("4. Hello \nPython")
print("5. Hello \rPython")
print("6. Hello \a Python")
print("7. Hello \\Python")
print("8. \ooo 20")
print("9. Hello \nPython")
print("10. Hello \bPython")
print("11. Hello \fPython")
print("12. Hello \vPython")
```

    1. Hello 'Python
    2. Hello "Python
    3. Hello 	Python
    4. Hello 
    Python
    Pythonlo 
    6. Hello  Python
    7. Hello \Python
    8. \ooo 20
    9. Hello 
    Python
    10. HelloPython
    11. Hello 
Python
    12. Hello 
Python


    <>:10: SyntaxWarning: invalid escape sequence '\o'
    <>:10: SyntaxWarning: invalid escape sequence '\o'
    /tmp/ipykernel_9809/2920431680.py:10: SyntaxWarning: invalid escape sequence '\o'
      print("8. \ooo 20")



```python

```


---
**Score: 10**