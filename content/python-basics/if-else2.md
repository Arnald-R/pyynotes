---
title: If-Else2
date: 2025-01-23
author: Your Name
cell_count: 17
score: 15
---

```python
#created at 20250123
```


```python
https://www.scientecheasy.com/2022/10/if-else-in-python.html/
```


```python
maths = int(input('Enter your maths marks: '))
```

    Enter your maths marks:  67



```python
phy = int(input('Enter your physics marks: '))
```

    Enter your physics marks:  87



```python
chem = int(input('Enter your chemistry marks: '))
```

    Enter your chemistry marks:  82



```python
total = chem + phy + maths
```


```python
per = total / 3
```


```python
print("Total marks obtained: ", total)
```

    Total marks obtained:  236



```python
print("Percentage: ", per)
```

    Percentage:  78.66666666666667



```python

if per >= 85:
    print("Grade A")
else:
    print("Grade B")
```

    Grade B



```python
num1, num2 = 20, 7
```


```python

if num1 % num2 == 0:
    print(num1, "is divisible by", num2)
else:
    print(num1, "is not divisible by", num2)

```

    20 is not divisible by 7



```python
num = int(input('Enter an integer number to check buzz: '))

```

    Enter an integer number to check buzz:  77



```python
if (num % 10 == 0) or (num % 7 == 0):
    print(num, "is a Buzz number")
else:
    print(num, "is not a Buzz number")
```

    77 is a Buzz number



```python
salary = 7500
```


```python
if salary >= 8000:
    salary = salary + (salary * 0.1)
    print("Employee salary: ", salary)
else:
    salary = salary + (salary * 0.15)
    print("Employee salary: ", salary)
```

    Employee salary:  8625.0



```python

```


---
**Score: 15**