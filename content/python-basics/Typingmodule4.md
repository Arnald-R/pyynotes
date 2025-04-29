---
title: Typingmodule4
date: 2025-04-29
author: Your Name
cell_count: 17
score: 15
---

```python
#created at 20250131
```


```python
https://chatgpt.com/c/679c622a-5318-800b-a323-68a368e854f9
```


```python
from typing import List
```


```python
def add_numbers(a: int, b: int) -> int:
    return a+b
```


```python
x: int = 10
y: int = 20
```


```python
z : str = "hello"
```


```python
print(add_numbers(x, y))
```

    30



```python
print(z)
```

    hello



```python
# Lists, Tuples, and Dictionaries
```


```python
from typing import List, Tuple, Dict
```


```python
numbers: List[int] = [1, 2, 3]
coordinates: Tuple[int, int] = (10, 20)
person: Dict[str,int] = {"age": 25,"height": 147}
```


```python
print(List, Tuple, Dict)
```

    typing.List typing.Tuple typing.Dict



```python
#Union
```


```python
from typing import Union
```


```python
def process_data(value: Union[int, float, str]) -> str:
    return f" processed :{value}"
```


```python
print(process_data(10))
print(process_data(3.14))
print(process_data("Arnald"))
```

     processed :10
     processed :3.14
     processed :Arnald



```python

```


---
**Score: 15**