---
title: Ex-6
date: 2025-03-19
author: Your Name
cell_count: 7
score: 5
---

```python
#creatd at 20250314
```


```python
#https://stevejoe1412.gitbook.io/ssn/python-subtopics/7.-function-annotations
```


```python
#Annotations for Callable objects
```


```python
from typing import Callable
```


```python
def execute(func : Callable[[int,int],int],a:int,b:int) -> int:
    return func(a,b)
```


```python
print(execute(lambda x,y: x+y,10,20))
```

    30



```python

```


---
**Score: 5**