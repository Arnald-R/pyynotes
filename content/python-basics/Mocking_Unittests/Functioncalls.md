---
title: Functioncalls
date: 2025-04-29
author: Your Name
cell_count: 5
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/10.-mocking-in-unit-tests
```


```python
from unittest.mock import Mock

mock_func = Mock()
mock_func(34) 
mock_func.asserted_called_with(34)
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[3], line 5
          3 mock_func = Mock()
          4 mock_func(34) 
    ----> 5 mock_func.asserted_called_with(34)


    File ~/miniconda3/envs/py312/lib/python3.12/unittest/mock.py:665, in NonCallableMock.__getattr__(self, name)
        663 if not self._mock_unsafe and (not self._mock_methods or name not in self._mock_methods):
        664     if name.startswith(('assert', 'assret', 'asert', 'aseert', 'assrt')) or name in _ATTRIB_DENY_LIST:
    --> 665         raise AttributeError(
        666             f"{name!r} is not a valid assertion. Use a spec "
        667             f"for the mock if {name!r} is meant to be an attribute.")
        669 with NonCallableMock._lock:
        670     result = self._mock_children.get(name)


    AttributeError: 'asserted_called_with' is not a valid assertion. Use a spec for the mock if 'asserted_called_with' is meant to be an attribute.



```python

```


```python


```


---
**Score: 5**