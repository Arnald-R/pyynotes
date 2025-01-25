---
title: If-Statement1
date: 2025-01-25
author: Your Name
cell_count: 18
score: 15
---

```python
#created at 20250123
```


```python
https://www.scientecheasy.com/2022/10/if-statement-in-python.html/
```


```python
num = int(input("Enter the number to check the number is divisble by 2"))
```

    Enter the number to check the number is divisble by 2 64



```python
if num % 2 == 0:
    print(num," is divisible by 2")
```

    64  is divisible by 2



```python
if num % 2 != 0:
    print(num ," is not divisble by 2")
```


```python
age = int(input(" enter your age to check you are eligible to vote or not: " ))
```

     enter your age to check you are eligible to vote or not:  19



```python
if age >= 18:
    print("you are eligible to cast a vote")
```

    you are eligible to cast a vote



```python
if age < 18 :
    print("you are not eligiblr to cast a vote")
```


```python
phy = int(input("Enter the physics marks: "))
```

    Enter the physics marks:  68



```python
chem = int(input("Enter the chemistry marks: "))
```

    Enter the chemistry marks:  81



```python
math = int(input("Enter the maths marks: "))
```

    Enter the maths marks:  69



```python
totalmarks = phy + chem + math
```


```python
myper = totalmarks /3
```


```python
print("total marks obtained is: ",totalmarks)
```

    total marks obtained is:  218



```python
print("the percentage is : ",myper)
```

    the percentage is :  72.66666666666667



```python
if (myper >= 90):
    print("Grade A")
```


```python
if(myper < 90.0): 
    print("Grade B")
```

    Grade B



```python

```


---
**Score: 15**