---
title: Functions
date: 2025-04-29
author: Your Name
cell_count: 15
score: 15
---

```python
#day 5
```


```python
def greet():
    print("Good Morning")
```


```python
greet()
```

    Good Morning



```python
def greet(name):
    print(f"hello,{name}")
```


```python
greet("Arnald")
```

    hello,Arnald



```python
def add(a, b):
    return a + b
```


```python
result = add( 3, 2)
```


```python
print(result)
```

    5



```python
result = add( 9, 1)
```


```python
print(result)
```

    10



```python
#  *args - variable number of positional arguments


def mul_numbers(*args):
    total = 1
    for num in args:
        total*= num
    return total

```


```python
print(mul_numbers(1, 3, 7, 9))
```

    189



```python
# **kwargs - variable number of keyword arguments

def info(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}:{value}")
        
```


```python
info(name ="Arnald", age = 23)
```

    name:Arnald
    age:23



```python

```


---
**Score: 15**