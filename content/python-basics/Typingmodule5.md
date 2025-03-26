---
title: Typingmodule5
date: 2025-03-26
author: Your Name
cell_count: 19
score: 15
---

```python
#created at 20250131
```


```python
https://chatgpt.com/c/679c622a-5318-800b-a323-68a368e854f9
```


```python
#Optional Type[Type,None]
```


```python
from typing import Optional
```


```python
def greet(name: Optional[str]) -> str:
    if name:
        return f"Hello,{name}!"
    return "Hello, Stranger!"
```


```python
print(greet("Arnald"))
```

    Hello,Arnald!



```python
print(greet(None))
```

    Hello, Stranger!



```python
#Callable (arguments and return type) 
```


```python
from typing import Callable
```


```python
def operation(x: int, y: int) -> int:
    return x + y
```


```python
def execute(func: Callable[[int,int], int],a: int,b: int) -> int:
    return func(a, b)
```


```python
print(execute(operation, 3 , 7))
```

    10



```python
#Generics
```


```python
from typing import TypeVar, Generic
```


```python
T = TypeVar('T')
```


```python
class Box(Generic[T]):
    def __init__(self, value : T ):
        self.value = value
    def get_value(self) -> T:
        return self.value
int_box = Box(199)
str_box = Box("Python")
```


```python
print(int_box.get_value())
```

    199



```python
print(str_box.get_value())
```

    Python



```python

```


---
**Score: 15**