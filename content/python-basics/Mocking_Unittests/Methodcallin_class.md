---
title: Methodcallin Class
date: 2025-02-10
author: Your Name
cell_count: 6
score: 5
---

```python
#created at 20250210

```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/10.-mocking-in-unit-tests
```


```python
from unittest.mock import Magicmock

class myClass:
    def method(self):
        return "Real World"

obj = MyClass()
obj.method = MagicMock(return_value= "Mocked method")
print(obj.method())
```


    ---------------------------------------------------------------------------

    ImportError                               Traceback (most recent call last)

    Cell In[4], line 1
    ----> 1 from unittest.mock import Magicmock
          3 class myClass:
          4     def method(self):


    ImportError: cannot import name 'Magicmock' from 'unittest.mock' (/home/arnald/miniconda3/envs/py312/lib/python3.12/unittest/mock.py)



```python

```


```python

```


```python

```


---
**Score: 5**