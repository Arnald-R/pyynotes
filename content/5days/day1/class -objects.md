---
title: Class -Objects
date: 2025-04-29
author: Your Name
cell_count: 10
score: 10
---

```python
#day 7
```


```python
#classes and objects
class Dog:
    def __init__(self, name, breed):
        self.name = name
        self.breed = breed

    def bark(self):
        return f"{self.name} barks"

#object creation
dog1 = Dog("Dora","Lab")
dog2 = Dog("diana", "puppy")
```


```python
print(dog1.bark())
```

    Dora barks



```python
print(dog2.bark())
```

    diana barks



```python
#    @classmethod -- 
class Student:
    school_name = "LMS school"

    def __init__(self,name, grade):
        self.name = name
        self.grade = grade

    @classmethod
    def change_school(cls, new_name):
        cls.school_name = new_name


print(Student.school_name)
```

    LMS school



```python
Student.change_school("ARB school")
```


```python
print(Student.school_name)
```

    ARB school



```python
#   @static method --do not access self or class

class MathOperations:
    @staticmethod
    def add(x, y):
        return x+y


    @staticmethod
    def multi(x, y):
        return x * y


print(MathOperations.add(3,8))

```

    11



```python
print(MathOperations.multi(3,10))
```

    30



```python

```


---
**Score: 10**