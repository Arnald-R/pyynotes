---
title: Typingmodule7
date: 2025-04-26
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
#NewType
```


```python
from typing import NewType
```


```python
UserId = NewType('UserId',int)
```


```python
def get_user(User_id: UserId) -> str:
    return f" user with id {User_id}"
```


```python
uid = UserId(101)
```


```python
print(get_user(uid))
```

     user with id 101



```python
#protocols
```


```python
from typing import Protocol
```


```python
class Speakable(Protocol):
    def speak(self) -> str:
        pass
    
```


```python
class Dog:
    def speak(self) -> str:
        return "woof!!"
```


```python
class Robot:
    def speak(seld) -> str:
        return "Beep,Beep"
```


```python
def make_speak(animal: Speakable) -> str:
    return animal.speak()
```


```python
dog = Dog()
```


```python
robot = Robot()
```


```python
print(make_speak(dog))
```

    woof!!



```python
print(make_speak(robot))
```

    Beep,Beep



```python

```


---
**Score: 15**