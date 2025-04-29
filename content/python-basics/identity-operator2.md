---
title: Identity-Operator2
date: 2025-04-29
author: Your Name
cell_count: 10
score: 10
---

```python
#created at 20250122
```


```python
https://www.scientecheasy.com/2022/10/identity-operators-in-python.html/
```


```python
num1 = 20
```


```python
num2 = 20
```


```python
print("num1 = ", num1, " ", "id(num1): ", id(num1))
```

    num1 =  20   id(num1):  9772200



```python
print("num2 = ", num2, " ", "id(num2): ", id(num2))
```

    num2 =  20   id(num2):  9772200



```python
if(id(num1) == id(num2)):
    print('num1 and num2 have the same identity')
else:
    print('num1 and num2 do not have the same identity')
```

    num1 and num2 have the same identity



```python
num2 = 40
print("num1 = ", num1, " ", "id(num1): ", id(num1))
print("num2 = ", num2, " ", "id(num2): ", id(num2))
```

    num1 =  20   id(num1):  9772200
    num2 =  40   id(num2):  9772840



```python
if(num1 is not num2):
    print('num1 and num2 do not have the same identity')
else:
    print('num1 and num2 have the same identity')

```

    num1 and num2 do not have the same identity



```python

```


---
**Score: 10**