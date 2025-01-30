---
title: Logical-Operator3
date: 2025-01-30
author: Your Name
cell_count: 25
score: 25
---

```python
#created at 20250122
```


```python
https://www.scientecheasy.com/2022/10/logical-operators-in-python.html/
```


```python
#logical or
```


```python
print((2 == 2) or (3 > 5))
```

    True



```python
print((5 > 18) or (3 != 9))
```

    True



```python
print((4 == 4) or (5 < 9))
```

    True



```python
print((4 < 2) or (2 == 1))
```

    False



```python
print((3 != 3) or (3 >= 9)) 
```

    False



```python
x, y ,z = 20, 10, 5
```


```python
if( x > y or y > z):
    print("python")
```

    python



```python
if( z > y  or y < x):
    print("java script")
```

    java script



```python
if((y+20) < x or (z + 15) < y):
    print("java")
```


```python
x, y, z = 10, 5, 20
```


```python
if((x > y) or (y == z)):
    print("one")
```

    one



```python
if((x == y) or (y < z)):
    print("two")
```

    two



```python
if((x != y) or (y != z)):
    print("three")
```

    three



```python
if((x < y) or (y > z)):
    print("Four")
```


```python
a = ("big " != "bigger") or False
```


```python
print("a :",a)
```

    a : True



```python
b = True or False
```


```python
print("b: ",b)
```

    b:  True



```python
c = "a" or D
```


```python
print("c: ", c)
```

    c:  a



```python
d = ("ABc" > "abC") or False
```


```python
print("d: ", d)
```

    d:  False



---
**Score: 25**