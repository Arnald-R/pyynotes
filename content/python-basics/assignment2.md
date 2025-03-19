---
title: Assignment2
date: 2025-03-19
author: Your Name
cell_count: 10
score: 10
---

```python
#data processing with union
```


```python
#Assignment 2: Data Processing with Union Types
Problem Statement:

Write a function that processes a list of items, where each item can be an int, float, or str. The function should return a list of strings describing each item.

Requirements:

Use the Union type from the typing module to annotate the parameter, indicating it can handle multiple types.
The function should iterate through the list and return a new list with strings describing the type and value of each item.
Include type annotations for the function parameters and return type.
Ensure type correctness using a static type checker.
```


```python
from typing import Union
```


```python
def process_list(value : Union[int, float, str]) -> str:
    return f"processed :{value}"
```


```python
print(process_list(1))
```

    <class 'str'>



```python
print(typ
```

    <class 'function'>



```python
print(process_list(19.23))
```

    processed :19.23



```python
print(process_list("Arnald"))
```

    processed :Arnald



```python
print(process_list)
```

    <function process_list at 0x74809025aac0>



```python

```


---
**Score: 10**