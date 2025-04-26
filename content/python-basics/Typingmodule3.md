---
title: Typingmodule3
date: 2025-04-26
author: Your Name
cell_count: 22
score: 20
---

```python
#created at 20250130
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/typing-module
```


```python
#using Tuple for fixed length sequences
```


```python
from typing import Tuple
```


```python
def process_coordinates(coords: Tuple[float, float]) -> str:
    return f"Latitude: {coords[0]},Latitude: {coords[0]}"
```


```python
print(process_coordinates((40.7128, -74.0060)))
```

    Latitude: 40.7128,Latitude: 40.7128



```python
#Using Any for Flexible Input

```


```python
from typing import Any
```


```python
def stringify(value: Any) -> str:
    return str(value)
```


```python
print(stringify(43))
```

    43



```python
print(stringify([1,2,3]))
```

    [1, 2, 3]



```python
#Using Literal for Specific Values
```


```python
from typing import Literal
```


```python
def choose_plan(plan: Literal["free", "enterprise", "premium"]) -> str: 
    return f"you selected the {plan} plan."
```


```python
print(choose_plan("premium"))
```

    you selected the premium plan.



```python
#Using TypedDict for Structured Dictionaries
```


```python
from typing import TypedDict
```


```python
class User(TypedDict):
    name: str
    age: int
    email: str
```


```python
def display_user(user: User) -> str:
    return f"{user['name']}({user['age']}) can be reached at {user['email']}."
```


```python
user = {"name": "Arnald", "age": 22, "email": "arnald642@gmail.com"}
```


```python
print(display_user(user))
```

    Arnald(22) can be reached at arnald642@gmail.com.



```python

```


---
**Score: 20**