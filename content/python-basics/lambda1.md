---
title: Lambda1
date: 2025-02-10
author: Your Name
cell_count: 11
score: 10
---

```python
#created at 20250203
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/lambda-functions
```


```python
add = lambda x, y: x + y
```


```python
print(add(5, 3)) 

```

    8



```python
#Lambda with Sorting

```


```python
data = [(1, 'apple'), (2, 'banana'), (3, 'cherry')]
sorted_data = sorted(data, key=lambda x: x[1])
print(sorted_data)
```

    [(1, 'apple'), (2, 'banana'), (3, 'cherry')]



```python
#Using Lambda with map()
```


```python
numbers = [1, 2, 3, 4, 5]
```


```python
result = map(lambda x: x * 2, numbers)
```


```python
print(list(result))  # Output: [2, 4, 6, 8, 10]
```


```python

```


---
**Score: 10**