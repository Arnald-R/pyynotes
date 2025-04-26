---
title: Ex-1-
date: 2025-04-26
author: Your Name
cell_count: 24
score: 20
---

```python
x = 4
result = "Even" if x % 2 == 0 else "Odd"
print(result)
```

    Even



```python
def greet(name):
    return f"Hello, {name}"

```


```python
print(greet("arnald"))
```

    Hello, arnald



```python
def func(*args, **kwargs):
    print(args)
    print(kwargs)

```


```python
def factorial(n):
    return 1 if n == 0 else n * factorial(n - 1)

```


```python
print(factorial(5))
```

    120



```python
def greet(name="Guest"):
    print("Hello", name)

```


```python
greet()
```

    Hello Guest



```python
def greet(name):      # ← 'name' is a **parameter**
    print(f"Hello, {name}!")

greet("Alice")         # ← "Alice" is an **argument**

```

    Hello, Alice!



```python
def add(a,b):
    return a+b

add(2, 3)
```




    5




```python
def add(a=2,b=3):
    return a+b


```


```python
print(add())
```

    5



```python
def greet(name ="Guest"):
    print(f"hi,{name}!")
```


```python
greet()
```

    hi,Guest!



```python
greet("Arnald")
```

    hi,Arnald!



```python
def maths(*args):
    for arg in args:
        print(arg)
```


```python
maths(1, 2, 3)
```

    1
    2
    3



```python
def key_maths(**kwargs):
    for key, value in kwargs.items():
        print(key, "=" , value)
        
```


```python
key_maths(name = "Arnald", Age = "23")
```

    name = Arnald
    Age = 23



```python
nums = [1, 2, 3]
result = list(map(lambda x: x*2, nums))  # [2, 4, 6]

```


```python
def decorator(func):
    def wrapper():
        print("Before")
        func()
        print("After")
    return wrapper

@decorator
def greet():
    print("Hello")

```


```python
greet()
```

    Before
    Hello
    After



```python
import unittest

class TestCalc(unittest.TestCase):
    def test_add(self):
        self.assertEqual(2 + 3, 5)

unittest.main()

```

    E
    ======================================================================
    ERROR: /home/arnald/ (unittest.loader._FailedTest./home/arnald/)
    ----------------------------------------------------------------------
    AttributeError: module '__main__' has no attribute '/home/arnald/'
    
    ----------------------------------------------------------------------
    Ran 1 test in 0.093s
    
    FAILED (errors=1)



    An exception has occurred, use %tb to see the full traceback.


    SystemExit: 1



    /home/arnald/miniconda3/envs/py312/lib/python3.12/site-packages/IPython/core/interactiveshell.py:3516: UserWarning: To exit: use 'exit', 'quit', or Ctrl-D.
      warn("To exit: use 'exit', 'quit', or Ctrl-D.", stacklevel=1)



```python

```


---
**Score: 20**