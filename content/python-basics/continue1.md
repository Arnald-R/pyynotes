---
title: Continue1
date: 2025-04-21
author: Your Name
cell_count: 6
score: 5
---

```python
#created at 20250125
```


```python
https://www.scientecheasy.com/2022/11/python-continue.html/

```


```python
x = 1
while x < 10:
    if x == 6:
        x = x + 1
        continue
    print(x)
    x = x + 1
```

    1
    2
    3
    4
    5
    7
    8
    9



```python
# Outer loop.
for x in range(1, 4):
   # Inner loop.
     for y in range(1, 4):
       if x == 2 and y == 3:
           continue # continue statement inside the inner for loop.
       print(x,y)

```

    1 1
    1 2
    1 3
    2 1
    2 2
    3 1
    3 2
    3 3



```python
for x in range(1, 7):
    if x < 2:
        continue
    print(x)
    if x < 4:
        continue
    print(10 * x)

```

    2
    3
    4
    40
    5
    50
    6
    60



```python

```


---
**Score: 5**