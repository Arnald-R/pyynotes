---
title: Lambda3
date: 2025-04-26
author: Your Name
cell_count: 23
score: 20
---

```python
#created at 20250203
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/lambda-functions
```


```python
#Lambda with Default Arguments
```


```python
greet = lambda name, greeting="Hello": f"{greeting}, {name}!"
```


```python
print(greet("Alice"))           # Output: Hello, Alice!
```

    Hello, Alice!



```python
print(greet("Alice", "Hi"))     # Output: Hi, Alice!
```

    Hi, Alice!



```python
def apply_func(func, x, y):
    return func(x, y)
```


```python
result = apply_func(lambda x, y: x ** y, 2, 3)
```


```python
print(result)  # Output: 8
```

    8



```python
#lambda with max and min
```


```python
words = ["apple", "banana", "cherry", "kiwi"]
```


```python
longest_word = max(words, key=lambda word: len(word))
```


```python
print(longest_word)  # Output: banana
```

    banana



```python
#Nested Lambda Functions
```


```python
multiply = lambda x: (lambda y: x * y)
```


```python
result = multiply(5)(2)
```


```python
print(result)  # Output: 10
```

    10



```python
#lambda for mathematical operation
```


```python
square = lambda x: x ** 2
```


```python
cube = lambda x: x ** 3
```


```python
print(square(4))  # Output: 16
```


```python
print(cube(3))
```

    27



```python

```


---
**Score: 20**