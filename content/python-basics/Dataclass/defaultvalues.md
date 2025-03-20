---
title: Defaultvalues
date: 2025-03-20
author: Your Name
cell_count: 10
score: 10
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/3.-data-classes
```


```python
#default values in data class
```


```python
from dataclasses import dataclass
```


```python
@dataclass
class Book:
    title : str
    author : str
    price : float = 99.20
book = Book(title = "Pybook",author = "Dennis Richie")
print(book)
```

    Book(title='Pybook', author='Dennis Richie', price=99.2)



```python

```


```python

```


```python

```


```python

```


```python

```


---
**Score: 10**