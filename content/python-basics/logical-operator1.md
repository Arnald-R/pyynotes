---
title: Logical-Operator1
date: 2025-03-26
author: Your Name
cell_count: 18
score: 15
---

```python
#created at 202250122
```


```python
https://www.scientecheasy.com/2022/10/logical-operators-in-python.html/
```


```python
print(20 > 10 and 30 < 40) # True. 
```

    True



```python
print(10 == 10 and 88 >= 78) # True.
```

    True



```python
print(10 == 20 and 50 <= 40) # False.
```

    False



```python
x, y = 10, 5 
```


```python
result = (x == 10 and y == 5)
```


```python
print(result)
```

    True



```python
result = (x == 10 and y > x)
```


```python
print(result)
```

    False



```python
result = (x < y and y > x)
```


```python
print(result)
```

    False



```python
# Use of logical and operator in the if statement.
```


```python
x, y, z = 20, 10, 25
```


```python
if(x > y and y > z):
    print("Hello")
```


```python
if(z > y and y < x):
    print("Python")
```

    Python



```python
if((y+200) < x and (y+150) < z):
    print("Hello Python")
```


```python

```


---
**Score: 15**