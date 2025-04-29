---
title: List3
date: 2025-04-29
author: Your Name
cell_count: 17
score: 15
---

```python
#created at 20250203
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/list-comprehensions
```


```python
#List Comprehension with Functions
```


```python
def square(x):
    return x**2
```


```python
numbers = [1, 2, 3, 4]
```


```python
square_numbers = [square(num) for num in numbers]
```


```python
print(square_numbers)
```

    [1, 4, 9, 16]



```python
# with conditional comprehension
```


```python
numbers = [1, 2, 3, 4, 5, 6]
```


```python
modified_numbers = [0 if num % 2 == 0 else num for num in numbers]
```


```python
print(modified_numbers)
```

    [1, 0, 3, 0, 5, 0]



```python
evens = [i for i in range (1, 21) if i%2 == 0]
```


```python
print(evens)
```

    [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]



```python
squares = [(i, i**2) for i in range(5)]
```


```python
print(squares)
```

    [(0, 0), (1, 1), (2, 4), (3, 9), (4, 16)]



```python
keys = [f'key{i}' for i in range(5)]
print(keys)  # Output: ['key0', 'key1', 'key2', 'key3', 'key4']
```

    ['key0', 'key1', 'key2', 'key3', 'key4']



```python

```


---
**Score: 15**