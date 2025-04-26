---
title: Validation
date: 2025-04-26
author: Your Name
cell_count: 5
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/4.-descriptor-protocols
```


```python
#descriptor with validation
```


```python
class PositiveNumber:
    
    def __get__(self, instance, owner):
        return instance._number
    def __set__(self, instance, value):
        if value < 0:
            raise ValueError("Number must be positive")
        instance._number = value
   
class MyClass:
    number = PositiveNumber()

obj = MyClass()
obj.number = 10
print(obj.number)
```

    10



```python

```


---
**Score: 5**