---
title: Literals
date: 2025-01-24
author: Your Name
cell_count: 24
score: 20
---

```python
#created at 20250120
```


```python
https://www.scientecheasy.com/2022/09/literals-in-python.html/
```


```python
#literals
```


```python
x=10
print(x)

```

    10



```python
#string literals
```


```python
singlt_line_string = 'asdf'
print(singlt_line_string )
multi_line_string = 'hi\
dear friend\
how are you'
print(multi_line_string )
```

    asdf
    hidear friendhow are you



```python
#integer literals
```


```python
x = 40
y = 0o34
z = 0x34
```


```python
print("Decimal representation ", x)
print("Decimal representation ", y)
print("Decimal representation ", z) 

```

    Decimal representation  40
    Decimal representation  28
    Decimal representation  52



```python
#floating point literals
```


```python
x = 56e-2
y = 0.56
print(x)
print(y)

```

    0.56
    0.56



```python
#complex literals
```


```python
a = 5 + 5j
b = 7j
print(a)
print(b)

```

    (5+5j)
    7j



```python
#boolean literal
```


```python
a = (9 == 9)
b = (5 == False)
c = True + 5
d = False + 5 

print("a is ", a)
print("b is ", b)
print("c is ", c)
print("d is ", d)

```

    a is  True
    b is  False
    c is  6
    d is  5



```python
# Special literals
a = None
print(a) 

```

    None



```python
#collection literal tokens, such as List, Tuple, Dictionary, and Set
list =mutable data or values of different types
```


```python
#<name of list> = [ <value1>, <value2>, <value3>, . . . . ]
# List literals
address = ['Arnald', 'Ambu', 'Anthony']
print(address)
list =[1,2,3,4,5,6,7,8,9]
print(list)

```

    ['Arnald', 'Ambu', 'Anthony']
    [1, 2, 3, 4, 5, 6, 7, 8, 9]



```python
#dictionary = stores value in a key-value pairs
```


```python
mark_list = { 
    'Arnsld' : 67,
    'ambu'   : 89,
    'anthony': 58}
print(mark_list)

```

    {'Arnsld': 67, 'ambu': 89, 'anthony': 58}



```python
# tuple literals
numbers = (90, 80, 68, 70, 95, 91)
vowels = ('a','r','n','o','l','d')
direction = ('North', 'South', 'East', 'West')

print(numbers)
print(vowels)
print(direction)

```

    (90, 80, 68, 70, 95, 91)
    ('a', 'r', 'n', 'o', 'l', 'd')
    ('North', 'South', 'East', 'West')



```python
#set literals
```


```python
num_reading = { 'nine','eight' ,'seven' ,'six'}
print(num_reading)
```

    {'seven', 'six', 'eight', 'nine'}



```python

```


---
**Score: 20**