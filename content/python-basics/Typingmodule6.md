---
title: Typingmodule6
date: 2025-04-21
author: Your Name
cell_count: 12
score: 10
---

```python
#created at 20250131
```


```python
https://chatgpt.com/c/679c622a-5318-800b-a323-68a368e854f9
```


```python
#TypedDict
```


```python
from typing import TypedDict
```


```python
class Person(TypedDict):
    name: str
    number: int
```


```python
p : Person = {"name": "Arnald","age": 22}
```


```python
print(p["name"],p["age"])
```

    Arnald 22



```python
#Literal type
```


```python
from typing import Literal
```


```python
def set_mode(mode: Literal["auto", "manual"]) -> str:
    return f"Mode set to {mode}"
```


```python
print(set_mode("auto"))
```

    Mode set to auto



```python

```


---
**Score: 10**