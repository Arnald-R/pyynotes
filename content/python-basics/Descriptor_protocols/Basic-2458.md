---
title: Basic-2458
date: 2025-02-10
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
#Basic Descriptor example
```


```python
 class Descriptor:
    def __get__(self, instance, owner):
        print("Getting value")
        return instance._value
    def __set__(self, instance, owner):
        print("setting value")
        instance._value = value 
 class Myclass:
    attribute = Descriptor()

obj = MyClass()
obj.attribute = 42
print(obj.attribute)
```

    Setting value
    Getting value
    42



```python

```


---
**Score: 5**