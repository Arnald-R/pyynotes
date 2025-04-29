---
title: Immutable 
date: 2025-04-29
author: Your Name
cell_count: 9
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/3.-data-classes
```


```python
#immutable dataclasses
```


```python
from dataclasses import dataclass
```


```python
@dataclass(frozen = True)
class Point:
    x : int
    y : int

point = Point(3, 4)
print(point)

```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[2], line 1
    ----> 1 @dataclass(frozen = True)
          2 class Point:
          3     x : int
          4     y : int


    NameError: name 'dataclass' is not defined



```python
from dataclasses import dataclass

@dataclass(frozen=True)
class Point:
    x: int
    y: int

point = Point(3, 4)
print(point)  # Output: Point(x=3, y=4)

# point.x = 5  # Raises error: FrozenInstanceError
```

    Point(x=3, y=4)



```python

```


```python

```


```python

```


---
**Score: 5**