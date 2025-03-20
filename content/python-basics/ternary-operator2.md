---
title: Ternary-Operator2
date: 2025-03-20
author: Your Name
cell_count: 21
score: 20
---

```python
#created at 20250123
```


```python
http://scientecheasy.com/2022/10/ternary-operator-in-python.html/
```


```python
age = int(input("How old are you? "))

```

    How old are you?  24



```python
eligible = "you are eligible" if(age >18) else "you are not eligible"
```


```python
print(eligible)
```

    you are eligible



```python
total = 0;
```


```python
yearcheck = int(input("Enter a leap year: "))
```

    Enter a leap year:  2025



```python
check4 = 1 if(yearcheck % 4 == 0) else 0
check100 = -1 if(yearcheck % 100 == 0) else 0
check400 = 1 if(yearcheck % 400 == 0) else 0
```


```python
total = check4 + check100 + check400
```


```python
print("leap year" if (total == 1) else "Not leap year")
```

    Not leap year



```python
num1 = int(input("Enter the first number: "))
```

    Enter the first number:  12



```python
num2 = int(input("Enter the second number: "))
```

    Enter the second number:  15



```python
print(num1, "is greater number") if (num1 > num2 ) else print(num2, "is great number")
```

    15 is great number



```python
# Nested ternary operator.
```


```python
num1, num2 = 10, 20
```


```python
num = "num1 = num2" if(num1 == num2) else "num1 > num2" if (num1 > num2) else "num2 > num1"
```


```python
print(num)
```

    num2 > num1



```python
# Nested if-else statement
```


```python
num1, num2 = 10, 20
```


```python
if num1 != num2:
    if num1 > num2:
        print("num1 > num2")
    else:
        print("num2 > num1")
else:
    print("num1 = num2")
```

    num2 > num1



```python

```


---
**Score: 20**