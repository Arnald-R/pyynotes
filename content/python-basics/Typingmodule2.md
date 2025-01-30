---
title: Typingmodule2
date: 2025-01-30
author: Your Name
cell_count: 17
score: 15
---

```python
#created at 20250130
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/typing-module
```


```python
# Using Union for Multiple Types

```


```python
from typing import Union
```


```python
def square_or_length(value: Union[int, str]) -> str:
    if isinstance(value, int):
        return value ** 2
    return len(value)
```


```python
print(square_or_length(4))
print(square_or_length("test"))
```

    16
    4



```python
#custom type aliases
```


```python
from typing import List
```


```python
vector = List[float]
```


```python
def dot_product(vec1 : vector, vec2 : vector) -> float:
    return sum(x * y for x , y in zip(vec1, vec2))
```


```python
print(dot_product([1.0, 2.0],[3.0, 4.0]))
```

    11.0



```python
#using callable functions
```


```python
from typing import Callable
```


```python
def apply_operation(a: int, b: int, operation: Callable[[int , int], int]) -> int:
    return operation(a,b)
```


```python
result = apply_operation(2, 3, lambda x, y: x + y)
```


```python
print(result)
```

    5



```python

```


---
**Score: 15**