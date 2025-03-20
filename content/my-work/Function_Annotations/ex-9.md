---
title: Ex-9
date: 2025-03-20
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
#Annotations for Generator Functions
```


```python
from typing import Generator
```


```python
def count_up_to(max_val : int) -> Generator[int, None, None]:
    count = 1
    while count <= max_val:
        yield count
        count += 1
```


```python
for num in count_up_to(5):
    print(num,end = " ")
```

    1 2 3 4 5 


```python

```


---
**Score: 5**