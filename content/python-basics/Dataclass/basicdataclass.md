---
title: Basicdataclass
date: 2025-03-26
author: Your Name
cell_count: 5
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/3.-data-classes
```


```python
from dataclasses import dataclass
```


```python
@dataclass
class Person:
    age :int
    name:str
person = Person(age = 30, name = "Arnlad")
print(person)
```

    Person(age=30, name='Arnlad')



```python

```


---
**Score: 5**