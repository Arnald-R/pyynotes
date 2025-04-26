---
title: Ex-9
date: 2025-04-26
author: Your Name
cell_count: 7
score: 5
---

```python
#created at 20250215
```


```python
#Class Methods
```


```python
print("\n === Class Methods ===")
```

    
     === Class Methods ===



```python
class Date:
    def __init__(self, year, month, day):
        self.year = year
        self.month = month
        self.date = day


    @classmethod
    def from_string(cls, date_string):
        year, month, day = map(int, date_string.split('-'))
        return cls(year, month, day)

    def __str__(self):
        return f"{self.year}-{self.month}-{self.day}"
```


```python
date = Date.from_string("2024-04-15")
```


```python
print(f"Date:{date}")
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[4], line 1
    ----> 1 print(f"Date:{date}")


    Cell In[2], line 14, in Date.__str__(self)
         13 def __str__(self):
    ---> 14     return f"{self.year}-{self.month}-{self.day}"


    AttributeError: 'Date' object has no attribute 'day'



```python

```


---
**Score: 5**