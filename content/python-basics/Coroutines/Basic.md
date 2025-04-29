---
title: Basic
date: 2025-04-29
author: Your Name
cell_count: 7
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/8.-coroutines
```


```python
def simple_coroutine():
    print("Coroutine started")
    x = yield
    print(f"Recieved: {x}")

coro = simple_coroutine()
next(coro)
coro.send(42)
```

    Coroutine started
    Recieved: 42



    ---------------------------------------------------------------------------

    StopIteration                             Traceback (most recent call last)

    Cell In[2], line 8
          6 coro = simple_coroutine()
          7 next(coro)
    ----> 8 coro.send(42)


    StopIteration: 



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