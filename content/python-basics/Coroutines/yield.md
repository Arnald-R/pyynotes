---
title: Yield
date: 2025-04-29
author: Your Name
cell_count: 4
score: 0
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/8.-coroutines
```


```python
def multi_yield_coroutine():
    print("corotine started")
    x = yield "First Field"
    print(f"Recieved: {x}")
    y= yield "Second Field"
    print(f"Recived: {y}")

coro = multi_yield_coroutine()
print(next(coro))
print(coro.send(10))
coro.send(20)
```

    corotine started
    First Field
    Recieved: 10
    Second Field
    Recived: 20



    ---------------------------------------------------------------------------

    StopIteration                             Traceback (most recent call last)

    Cell In[3], line 11
          9 print(next(coro))
         10 print(coro.send(10))
    ---> 11 coro.send(20)


    StopIteration: 



```python

```


---
**Score: 0**