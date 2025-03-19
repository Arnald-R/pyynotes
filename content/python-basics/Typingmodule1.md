---
title: Typingmodule1
date: 2025-03-19
author: Your Name
cell_count: 17
score: 15
---

```python
#created at 20250130
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/typing-module
```


```python
#Specifying Function Input and Output Types
```


```python
from typing import List
```


```python
def sum_of_integers(numbers: List[int]) -> int:
    return sum(numbers)
```


```python
print(sum_of_integers([1, 2, 3]))
```

    6



```python
#Using Optional for Nullable Parameters
```


```python
from typing import Optional
```


```python
def greet(name: Optional[str] = None) -> str:
    if name:
        return f"Hello, {name}!"
    return "Hello,Guest!"
    
```


```python
print(greet())
```

    Hello,Guest!



```python
print(greet("Alice"))
```

    Hello, Alice!



```python
#Hint for dictionaries
```


```python
from typing import Dict
```


```python
def count_fruits(fruit_counts: Dict[str,int]) -> int :
    return sum(fruit_counts.values())
```


```python
fruits = {"apple": 5,"banana": 6,"watermelon" :10}
```


```python
print(count_fruits(fruits))
```

    21



```python

```


---
**Score: 15**