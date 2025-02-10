---
title: List2
date: 2025-02-10
author: Your Name
cell_count: 11
score: 10
---

```python
#created at 20250203
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/list-comprehensions
```


```python
#List Comprehension with Multiple Iterators
```


```python
a = [1,2,3]
```


```python
b = ['x','y']
```


```python
product = [(i ,j) for i in a for j in b]
print(product)
```

    [(1, 'x'), (1, 'y'), (2, 'x'), (2, 'y'), (3, 'x'), (3, 'y')]



```python
#Nested List Comprehensions
```


```python
matrix = [[1,2],[3,4],[5,6]]
```


```python
flattened = [ item for sublist in matrix for item in sublist]
```


```python
print(flattened)
```

    [1, 2, 3, 4, 5, 6]



```python

```


---
**Score: 10**