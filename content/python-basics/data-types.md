---
title: Data-Types
date: 2025-03-20
author: Your Name
cell_count: 22
score: 20
---

```python
#created at 20250120
```


```python
https://www.scientecheasy.com/2022/09/data-types-in-python.html/
```


```python
#int,float,complex
```


```python
num1 = 20
num2 = 30
add  = num1 + num2 
print(add)
```

    50



```python
num1 = 20.55
num2 = 29.99
add  = num1 + num2
print(add)
```

    50.54



```python
num1 = 23E5
num2 = 27E5
add  = num1 + num2
print(add)
```

    5000000.0



```python
num1 = 3+7j
num2 = 2+8j
add  = num1 +num2
print(add)
```

    (5+15j)



```python
num1 =12
num2 = 78.09
num3 =78E5
num4 =7+7j
print(num1)
print(num2)
print(num3)
print(num4)
print(type(num1))
print(type(num2))
print(type(num3))
print(type(num4))
print(isinstance(num3,float))
```

    12
    78.09
    7800000.0
    (7+7j)
    <class 'int'>
    <class 'float'>
    <class 'float'>
    <class 'complex'>
    True



```python
#boolean
```


```python
a = (10>=15)
b = (10 == 10 * 3)
c = (10 != 3 * 2)
print(a,b,c)
```

    False False True



```python
a = True
b = True * False
c = 5+True
d = True + 10
print(b,c,d)
print(type(a))

```

    0 6 11
    <class 'bool'>



```python
a = None
print(a)
print(type(a))
```

    None
    <class 'NoneType'>



```python
#string
str1 = "Good morning"
str2 = "hi friends hope doing well"
print(str1)
print(str2)
print(type(str1))
```

    Good morning
    hi friends hope doing well
    <class 'str'>



```python
store = [10, 20.50, "Python", True]
print(store)
print(type(store))

```

    [10, 20.5, 'Python', True]
    <class 'list'>



```python
number_list = [10,20,32,34]
print(number_list)
number_list[2] = 50
print(number_list)
```

    [10, 20, 32, 34]
    [10, 20, 50, 34]



```python
#tuple
```


```python
t = (1,2.5,"Arnald",4+3j)
print(t)
print(type(t))
```

    (1, 2.5, 'Arnald', (4+3j))
    <class 'tuple'>



```python
#set
```


```python
s = {1,2.7,"jack",5+6j}
print(s)
print(type(s))
```

    {1, 2.7, 'jack', (5+6j)}
    <class 'set'>



```python
#dict  
```


```python
veg = {1 :'brinjal',
       2 :'carrot',
       'veg3' :'tomato'}
print(veg)
print(type(veg))
```

    {1: 'brinjal', 2: 'carrot', 'veg3': 'tomato'}
    <class 'dict'>



```python
    
```


---
**Score: 20**