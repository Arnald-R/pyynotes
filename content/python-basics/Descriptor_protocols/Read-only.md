---
title: Read-Only
date: 2025-04-29
author: Your Name
cell_count: 4
score: 0
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/4.-descriptor-protocols
```


```python
class ReadOnlyDescriptor:
    def __get__(self, instance, owner):
        return "This is a read-only attribute"
    def __set__(self, instance, owner):
        raise AttributeError("Cannot modify read-only attribute")

class MyClass:
    read_only = ReadOnlyDescriptor()

obj = MyClass()
print (obj.read_only)
```

    This is a read-only attribute



```python

```


---
**Score: 0**