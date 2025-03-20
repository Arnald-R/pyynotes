---
title: Assignment3
date: 2025-03-20
author: Your Name
cell_count: 6
score: 5
---

```python
#Dictionary data aggregation
```


```python
from typing import Dict
```


```python
def subject_marks(subject_marks: Dict[str,int]) -> int :
    return sum(subject_marks.values())
```


```python
marks = {"tamil": 91,"english": 93,"maths" :91}
```


```python
print(subject_marks(marks))
```

    275



```python

```


---
**Score: 5**