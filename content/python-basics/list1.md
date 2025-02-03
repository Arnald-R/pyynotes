---
title: List1
date: 2025-02-03
author: Your Name
cell_count: 12
score: 10
---

```python
#created at 20250203
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/list-comprehensions
```


```python
#Basic list comprehension
```


```python
squares = []
for i in range(5):
    squares.append(i**2)
```


```python
squares = [i**2 for i in range(5)]
print(squares)  # Output: [0, 1, 4, 9, 16]
```

    [0, 1, 4, 9, 16]



```python
#list comprehension with conditional logic
```


```python
evens = [i for i in range(10) if i % 2 == 0]
print(evens)  # Output: [0, 2, 4, 6, 8]
```

    [0, 2, 4, 6, 8]



```python
# Convert a list of strings to uppercase
```


```python
words = ['hello', 'world', 'python']
```


```python
uppercase_words = [word.upper() for word in words]
```


```python
print(uppercase_words)  # Output: ['HELLO', 'WORLD', 'PYTHON']
```


```python

```


---
**Score: 10**