---
title: Nested-If2
date: 2025-03-19
author: Your Name
cell_count: 8
score: 5
---

```python
#created at 20250124
```


```python
https://www.scientecheasy.com/2022/10/python-nested-if.html/
```


```python
num = int(input("Enter the number to check divisible"))
```

    Enter the number to check divisible 56



```python
if num % 2 == 0:
    if num % 3 ==0:
        print(" The num is divisible by 2 and 3")
    else:
        print("The num is divisible by 2 not 3")
else:
    if num % 3 == 0:
        print("the number is divisble by 3 not 2")
    else:
        print("number is not divisible by 3 and 2")
```

    The num is divisible by 2 not 3



```python
if num >= 0:
    if num == 0:
        print(" the number is zer")
    else:
        print(" the number is positive")
else:
    print("Number is negative")
```

     the number is positive



```python
age =int(input(" Enter the age to check :"))
```

     Enter the age to check : 48



```python
if age < 18:
    print(" you are minor not eligible to cast vote") 
else: 
    if age > 18 and age < 60:
        print("you are young and eligible to cast vote")
    else:
        print("you are senior citizen and eligible to vote")
```

    you are young and eligible to cast vote



```python

```


---
**Score: 5**