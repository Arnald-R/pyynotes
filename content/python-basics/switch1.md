---
title: Switch1
date: 2025-04-21
author: Your Name
cell_count: 9
score: 5
---

```python
#createdat 20250125
```


```python
https://www.scientecheasy.com/2022/11/switch-statement-in-python.html/
```


```python
x = int(input("enter the first number:"))
```

    enter the first number: 21



```python
y = int(input("enter the second number:"))
```

    enter the second number: 21



```python
choice =int(input(" enter the choice 1.addition 2.subtraction 3.division 4.multiplication"))
```

     enter the choice 1.addition 2.subtraction 3.division 4.multiplication 2



```python
def addition():
    sum = x + y
    return sum
def subtraction():
    sub = x - y
    return sub
def division():
    div = x / y
    return div
def multiplication():
    mul = x * y
    return mul
def default():
    return "you selected the wrong operation"

```


```python
switcher = {
    1 : addition,
    2 : subtraction,
    3 : division,
    4 : multiplication
}
```


```python
def switch(num):
    return switcher.get(num,default)()
print (switch(choice)) 
```

    0



```python

```


---
**Score: 5**