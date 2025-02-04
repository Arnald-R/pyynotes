---
title: Nested-If1
date: 2025-02-04
author: Your Name
cell_count: 12
score: 10
---

```python
#createdat 20250124
```


```python
https://www.scientecheasy.com/2022/10/python-nested-if.html/
```


```python
#when outer true means get into the inner if
```


```python
x = 15
```


```python
y = 10
```


```python
z = 5
```


```python
if x > y:
    if y > z:
        print("Hi")
```

    Hi



```python
if x > y:
    if y < z:
        print("Heloo")
    print("Hi")
```

    Hi



```python
#if first condition fails means it doesnot get into the inner 
```


```python
if x < y:
    if y > z:
        print("Hi")
    print("Hello")
```


```python
if x < y:
    print("outer if")
    if y > z:
        print("inner if")
    else:
        print("inner if-else")
else:
    print("outer if-else")
```

    outer if-else



```python

```


---
**Score: 10**