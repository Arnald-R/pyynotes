---
title: Multimetgods
date: 2025-03-19
author: Your Name
cell_count: 5
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/5.-abstract-base-classes-abcs
```


```python
#abstract class with multiple methods
```


```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass

    @abstractmethod
    def perimeter(self):
        pass

class Rectangle(Shape):
    def __init__(self, width, height):
        self.width = width
        self.height = height

    def area(self):
        return self.width * self.height

    def perimeter(self):
        return 2 * (self.width + self.height)

rect = Rectangle(4, 5)
print(rect.area())       # Output: 20
print(rect.perimeter())  # Output: 18
```

    20
    18



```python

```


---
**Score: 5**