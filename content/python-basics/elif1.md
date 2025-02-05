---
title: Elif1
date: 2025-02-05
author: Your Name
cell_count: 16
score: 15
---

```python
#createdat 20250124
```


```python
https://www.scientecheasy.com/2022/10/python-if-elif-else.html/
```


```python
print("math operations")
print("----------------")
print("+ => Addition")
print("- => Subtraction")
print("* => Multiplication")
print("/ => Division")
```

    math operations
    ----------------
    + => Addition
    - => Subtraction
    * => Multiplication
    / => Division



```python
opt = input("Enter a input [+,-,*,/]: ")
```

    Enter a input [+,-,*,/]:  *



```python
num1 = int(input("Enter the first number: "))
```

    Enter the first number:  54



```python
num2 = int(input("Enter the Second number: "))
```

    Enter the Second number:  34



```python
if (opt == '+' ):
    num = num1 + num2
    print("sum of" ,num1 ,"and" ,num2, "is :" ,num)
elif (opt == '-'):
    num = num1 - num2
    print("sub of" ,num1, "and" ,num2 ," is  :",num)
elif (opt == '*'):
    num = num1 * num2
    print("multi of" ,num1, "and" ,num2 ,"is :", num)
else:
    num = num1/num2
    print("division of" ,num1, "and", num2, "is :",num) 
```

    multi of 54 and 34 is : 1836



```python
math = int(input("Enter the maths marks:"))
```

    Enter the maths marks: 89



```python
phy = int(input("Enter the phys marks:"))
```

    Enter the phys marks: 91



```python
chem = int(input("Enter the Chem marks:"))
```

    Enter the Chem marks: 67



```python
total = math + phy + chem
```


```python
per = total / 3
```


```python
print(total)
```

    247



```python
print(per)
```

    82.33333333333333



```python
if( per > 90):
    print("Grade A")
elif( per > 80):
    print("Grade B")
elif( per > 70):
    print("Grade C")
else:
    print("Grade D")
```

    Grade B



```python

```


---
**Score: 15**