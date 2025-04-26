---
title: Basic-5749
date: 2025-04-26
author: Your Name
cell_count: 7
score: 5
---

```python
#created at 20250210
```


```python
#https://stevejoe1412.gitbook.io/ssn/python-subtopics/5.-abstract-base-classes-abcs
```


```python
#Basic abstract base class
```


```python
from abc import ABC, abstractmethod
class Animal(ABC):
    @abstractmethod
    def make_sound(self):
        pass

class Dog(Animal):
    def make_sound(self):
        return "woof" 

dog = Dog()
print(dog.make_sound())
```

    woof



```python

```


```python

```


```python

```


---
**Score: 5**