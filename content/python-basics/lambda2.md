---
title: Lambda2
date: 2025-02-03
author: Your Name
cell_count: 17
score: 15
---

```python
#created at 20250203
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/lambda-functions
```


```python
#using lambda with filter()
```


```python

```


```python
numbers = [1, 2, 3, 4, 5, 6]
```


```python
result = filter(lambda x: x % 2 == 0, numbers)
```


```python
print(list(result))  # Output: [2, 4, 6]
```

    [2, 4, 6]



```python
#using lambda with reduce()
```


```python
from functools import reduce
```


```python
numbers = [1, 2, 3, 4, 5]
```


```python
result = reduce(lambda x, y: x * y, numbers)
```


```python
print(result)  # Output: 120
```

    120



```python
#Lambda with Default Arguments
```


```python
def apply_func(func, x, y):
    return func(x, y)
```


```python
result = apply_func(lambda x, y: x ** y, 2, 3)
```


```python
print(result) 
```

    8



```python

```


---
**Score: 15**