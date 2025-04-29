---
title: Exception-Handling
date: 2025-04-29
author: Your Name
cell_count: 6
score: 5
---

```python
#Day6
```


```python
Exception Handling - when your program encoubters an error (exception) using exxception handling we can fix the error and handle 
```


```python
try:
    x = 5/0
except ZeroDivisionError:
    print('you can not divide by zero')
```

    you can not divide by zero



```python
try:
    num = int(input("Enter the number:"))
    result = 10/num
except ZeroDivisionError:
    print("Zero cannot be divide ")
except ValueError:
    print("The Invalid input Error")
```

    Enter the number: a


    The Invalid input Error



```python
try:
    num = int(input("Enter the number:"))
    result = 10/num
except ZeroDivisionError:
    print("Zero cannot be divide ")
except ValueError:
    print("The Invalid input Error")
finally:
    print("execution completed")
```

    Enter the number: 0


    Zero cannot be divide 
    execution completed



```python

```


---
**Score: 5**