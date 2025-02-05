---
title: Switch
date: 2025-02-05
author: Your Name
cell_count: 10
score: 10
---

```python
#created at 20250125
```


```python
https://www.scientecheasy.com/2022/11/switch-statement-in-python.html/
```


```python
city = 'a'
```


```python
if city == 'k':
    print("karna")
elif city == 'g':
    print("germany")
elif city == 'h':
    print("hankok")
elif city == 'a':
    print("andhra")
else:
    print("no city")
```

    andhra



```python
# Implementing switch case statement in Python using Dictionary.
```


```python
def m():
    return "madurai"
def d():
    return "dharmapuri"
def c():
    return "chengalpet"
def r():
    return "ranipet"
def default():
    return "nocity"
```


```python
# Creating a dictionary and put these in it.
switcher = {
    1: m,
    2: d,
    3: c,
    4: r
    }
```


```python
def switch(city):
    return switcher.get(city, default)()
```


```python
print(switch(2)) # Calling function.
print(switch(3)) # Calling function.
```

    dharmapuri
    chengalpet



```python

```


---
**Score: 10**