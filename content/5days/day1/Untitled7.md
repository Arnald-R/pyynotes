---
title: Untitled7
date: 2025-04-29
author: Your Name
cell_count: 14
score: 10
---

```python
#day8
```


```python
#Inheritance - One class occurs the all the behaviour of the parent class is known as Inheritance
```


```python
class Animal:
    def __init__(self, name):
        self.name = name

    def speak(self):
        return f"{self.name} makes a sound"


#Dog inherits  from Animal
class Dog(Animal):
    def speak(self):
        return f"{self.name} barks"

#Cat inherits from Animal
class Cat(Animal):
    def speek(self):
        return f"{self.name} meow"
```


```python
dog = Dog("Bino")
```


```python
cat = Cat("sintu")
```


```python
print(dog.speak())
```

    Bino barks



```python
print(cat.speak())
```

    sintu makes a sound



```python
#Polymorphism - same function name, in different claasses and performed by many ways

```


```python
for animal in [Dog("Bino"), Cat("sintu")]:
    print(animal.speak())
```

    Bino barks
    sintu makes a sound



```python
#Encapsulation - Hiding the implementation details and storing the personality of the user

_  protected
__ private
```


```python
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance

    def deposit(self, Amount):
        self.__balance += Amount

    def get_balance(self):
        return self.__balance

account = BankAccount(1000)
```


```python
account.deposit(500)
```


```python
print(account.get_balance())
```

    1500



```python

```


---
**Score: 10**