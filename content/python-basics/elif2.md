---
title: Elif2
date: 2025-02-04
author: Your Name
cell_count: 12
score: 10
---

```python
#created at 20250124
```


```python
https://www.scientecheasy.com/2022/10/python-if-elif-else.html/
```


```python
age = int(input("Enter the age: "))
```

    Enter the age:  30



```python
if age < 18:
    print(age ,"- you are a child")
elif age > 18 and age < 60:
    print(age , "- you are an adult")
elif age > 60:
    print(age ," - yor a senior")
else:
    print("you have entered a invalid age")
```

    30 - you are an adult



```python
ch = input("Enter the single character: ")
```

    Enter the single character:  p



```python
if ch == 'a' or ch == 'A':
    print( ch ," - is a vowel")
elif ch == 'e' or ch == 'E':
    print( ch ," -is a vowel")
elif ch == 'i' or ch == 'I':
    print( ch ," - is a vowel")
elif ch == 'o' or ch == 'O':
    print( ch ," - is a vowel")
elif ch == 'u' or ch == 'U':
    print( ch ," - is a vowel")
else:
    print(ch ,"- is a consonent")
```

    p - is a consonent



```python
#three sides of triangle input
```


```python
side1 =int(input("enter the first side value: "))
```

    enter the first side value:  12



```python
side2 = int(input("enter the second side value: "))
```

    enter the second side value:  12



```python
side3 = int(input("enter the third side value: "))
```

    enter the third side value:  38



```python
if ((side1 != side2) and (side1 != side3) and (side2 != side3)):
    print("the triangle is scalene triangle")
elif ((side1 == side2) and (side2 == side3)) :
    print("the triangle is equilateral triangle")
else:
    print("the triangle is isosceles triangle")
```

    the triangle is isosceles triangle



```python

```


---
**Score: 10**