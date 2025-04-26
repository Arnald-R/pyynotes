---
title: Identity-Operator1
date: 2025-04-26
author: Your Name
cell_count: 36
score: 35
---

```python

```


```python

```


```python
#created at 20250122
```


```python
https://www.scientecheasy.com/2022/10/identity-operators-in-python.html/
```


```python
list1 = [20, 30.5, 40, 'text'] 
```


```python
list2 = [20, 30.5, 40, 'text']
```


```python
result = list1 is list2
```


```python
print(result)
```

    False



```python
dict1 = {
    'name': 'jack',
    'age': 20,
}
```


```python
dict2 = {
    'name':'jack',
    'age':20,
}

```


```python
result = dict1 is dict2
```


```python
print(result)
```

    False



```python
tuple1 = (1, 2.3, 5,'Tech')
```


```python
tuple2 = (1, 2.3, 5,'Tech')
```


```python
result = tuple1 is tuple2
```


```python
print(result)
```

    False



```python
#is not operator
```


```python
num1 = 30
```


```python
num2 = 40
```


```python
print(num1 is not num2)
```

    True



```python
num2 = 30
```


```python
print(num1 is not num2)
```

    False



```python
str1 = 'python'
```


```python
str2 = 'Langchain'
```


```python
print(str1 is not str2)
```

    True



```python
list1 = [2, 4, 6, 8, 10]
```


```python
list2 = [12, 14, 16]
```


```python
print(list1 is not list2)
```

    True



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
if(num1 is num2):
    print('num1 and num2 have the same identity')
else:
    print('num1 and num2 do not have the same identity')
```

    num1 and num2 have the same identity



```python
if(id(num1) == id(num2)):
    print('num1 and num2 have the same identity')
else:
    print('num1 and num2 do not have the same identity')
```

    num1 and num2 have the same identity



```python
if(num1 is not num2):
    print('num1 and num2 do not have the same identity')
else:
    print('num1 and num2 have the same identity')

```

    num1 and num2 have the same identity



```python

```


---
**Score: 35**