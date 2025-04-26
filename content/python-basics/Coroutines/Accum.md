---
title: Accum
date: 2025-04-26
author: Your Name
cell_count: 5
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/8.-coroutines
```


```python
#accumulating values
```


```python
def accumulator():
    total = 0
    while True:
        value = yield total
        total += value

coro = accumulator()
next(coro)
print(coro.send(10))
print(coro.send(4))
print(coro.send(24))
```

    10
    14
    38



```python

```


---
**Score: 5**