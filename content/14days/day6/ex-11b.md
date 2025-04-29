---
title: Ex-11B
date: 2025-04-29
author: Your Name
cell_count: 8
score: 5
---

```python
#created at 20250415
```


```python
#Magic Methods
```


```python
print("\n === Magic Methods ===")
```

    
     === Magic Methods ===



```python
class Point:
    def __init__(self, x, y):
        self.x = x
        self.y = y

    def __str__(self):
        return f"Point({self.x}, {self.y})"

    def __add__(self, other):
        return Point(self.x + other.x, self.y + other.y)
        
```


```python
p1 = Point(1, 2)
```


```python
p2 = Point(2, 3)
```


```python
print(f"sum of points:{ p1 + p2}")
```

    sum of points:Point(3, 5)



```python

```


---
**Score: 5**