---
title: Ex-11A
date: 2025-04-21
author: Your Name
cell_count: 6
score: 5
---

```python
#created at 20250415
```


```python
#Property decorators
```


```python
print("\n === Property Decorators === ")
```

    
     === Property Decorators === 



```python
class Temperature:
    def __init__(self, celsius):
        self._celsius = celsius

    @property
    def celsius(self):
        return self._celsius

    @property
    def fahrenheit(self):
        return (self._celsius * 9/5) + 32

    @fahrenheit.setter
    def fahrenheit(self, value):
        self._celsius = (value - 32) * 5/9

temp = Temperature(25)
print(f"temparture:{temp.celsius}")
print(f"fahrenheit:{temp.fahrenheit}")
```

    temparture:25
    fahrenheit:77.0



```python
        
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[3], line 1
    ----> 1 temp = Temperature(25)


    Cell In[2], line 3, in Temperature.__init__(self, celsius)
          2 def __init__(self, celsius):
    ----> 3     self.celsius = celsius


    AttributeError: property 'celsius' of 'Temperature' object has no setter



```python

```


---
**Score: 5**