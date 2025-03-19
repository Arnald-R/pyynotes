---
title: Ex-5
date: 2025-03-19
author: Your Name
cell_count: 8
score: 5
---

```python
#creatd at 20250314
```


```python
#https://stevejoe1412.gitbook.io/ssn/python-subtopics/7.-function-annotations
```


```python
#Annotations for Optional parameters
```


```python
from typing import Optional
```


```python
def find_user(username : str , age :Optional[int] = None ) -> str:
    return f"User:{username} , Age : {age if age else 'unknown'}"
```


```python
print(find_user("Arnald"))
```

    User:Arnald , Age : unknown



```python
print(find_user("Ambu",32))
```

    User:Ambu , Age : 32



```python

```


---
**Score: 5**