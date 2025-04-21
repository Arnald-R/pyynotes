---
title: Logical-Operator4
date: 2025-04-21
author: Your Name
cell_count: 14
score: 10
---

```python
#createdat 20250122
```


```python
https://www.scientecheasy.com/2022/10/logical-operators-in-python.html/
```


```python
#logical not
```


```python
if(not(2 > 5)):
     print("I love Python Programming")
```

    I love Python Programming



```python
print(not(5 == 5))
```

    False



```python
print(not(False))
```

    True



```python
print(not(True))
```

    False



```python
a = not("ABc" > "ABC") or False
print("a: ", a)
```

    a:  False



```python
b = not(True) or not(False)
print("b: ",b)
```

    b:  True



```python
c = (True >= 0) or not(20 == 20)
print("c :",c)
```

    c : True



```python
d = not("5" == 10) and not(False and (10 != 20))
print("d :",d)
```

    d : True



```python
a = not("abc" < "ABCD") and not(False)
print("a :",a)
```

    a : True



```python
b = not True and not False
print("b :",b)
```

    b : False



```python
c = not("20" == 20) and not(True == False)
print("c :",c)
```

    c : True



---
**Score: 10**