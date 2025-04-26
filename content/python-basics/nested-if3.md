---
title: Nested-If3
date: 2025-04-26
author: Your Name
cell_count: 15
score: 15
---

```python
#created at 20250124
```


```python
https://www.scientecheasy.com/2022/10/python-nested-if.html/
```


```python
year = int(input("enter the year to check leap year:"))
```

    enter the year to check leap year: 2027



```python
if year % 4 == 0:
    if year % 100 == 0:
        if year % 400 == 0:
            print(year," is a leap year")
        else:
            print(year," is not leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"is not leap year")
```

    2027 is not leap year



```python
opr = input('Please enter an operator [+, -, *, or /]: ')
```

    Please enter an operator [+, -, *, or /]:  *



```python
if ( opr == '+' or opr == '-' or opr == '*' or opr == '/'):
    n1 = int(input(" please enter the first number:"))
    n2 = int(input(" please enter the second number:"))
    if(opr == '+'):
        sum = n1 + n2
        print("sum of", n1, "and ",n2, '= ',sum)
    elif(opr == '-'):
        if(n1 > n2):
            diff = n1 - n2
        else:
            diff = n2 - n1
        print("Differnce between",n1,"and",n2," = ",diff)
    elif(opr == '*'):
        multiply = n1 * n2
        print('Multiplication of',n1,'and',n2,'=', multiply)
    elif(opr == '/'):
        if(n1 == 0 or n2 == 0):
            print('Numbers must be positive.')
        else:
            div = n1 / n2
            print('Division of',n1,'by',n2,'=', div)
else:
    print('Sorry, you have entered an invalid operator. Please choose any of these +, -, *, or /.')

```

     please enter the first number: 56
     please enter the second number: 67


    Multiplication of 56 and 67 = 3752



```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


---
**Score: 15**