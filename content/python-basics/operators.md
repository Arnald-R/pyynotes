---
title: Operators
date: 2025-03-26
author: Your Name
cell_count: 21
score: 20
---

```python
#createdat 20250121
```


```python
https://www.scientecheasy.com/2022/10/operators-in-python.html/
```


```python
#addition operators
```


```python
x = 20

```

    sum of 'x' and 'y' is: 50



```python
y = 30
```


```python
sum = x + y
print("sum of 'x' and 'y' is:",sum)
```


```python
#converts decimal into integer
```


```python
x = 20 
y = 30.60 
sum = x + y 
print("Sum of two numbers: ", sum) 

```

    Sum of two numbers:  50.6



```python
#string concatentaion 
firstname = "Arnald"
lastname = "Ramesh"
fullname = firstname + lastname
print("fullname:",fullname)
```

    fullname: ArnaldRamesh



```python
#list concatentation
x = [1,2,3,4]
y = [4,56,6,9]
add = x + y
print(add)
```

    [1, 2, 3, 4, 4, 56, 6, 9]



```python
x = ('Hi', 22)
y = (12, 'Arnald')
z = (7, 2002)
result = x + y + z
print(result)

```

    ('Hi', 22, 12, 'Arnald', 7, 2002)



```python
#subtraction
x = 34.50
y = 45
sub = x - y
print("subtraction:",sub)
```

    subtraction: -10.5



```python
#multiplication
x = 10
y = 30
mul = x * y
print("multiplication:",mul)
```

    multiplication: 300



```python
text = 'hello'
count = 3
result = text * 3
print("result is to be:",result)
```

    result is to be: hellohellohello



```python
list = ['hi','Arnald']
y = 2
result = list * 2
print("list is:",result)
```

    list is: ['hi', 'Arnald', 'hi', 'Arnald']



```python
#division
x = 20
y = 3
print(x/y)
x = 12.6
y = 4.2
print(x/y)
```

    6.666666666666667
    3.0



```python
#modulus
num1 = 20
num2 = 3
print(num1 % num2)
x = 3.6
y = 1.4
print(x % y)
```

    2
    0.8000000000000003



```python
#exponential op(**)
num1 = 6
num2 = 3
exp = num1 ** num2
print("expo:",exp)
x = 2.3
y = 3
exp = x ** y
print("expo:",exp)

```

    expo: 216
    expo: 12.166999999999998



```python
#floor division it cuts the division after the decimal
num1 = 5
num2 = 2
num = num1 // num2
print("Result: ", num)

x = 12.2
y = 3.1
z = x // y
print("Result: ", z)

```

    Result:  2
    Result:  3.0



```python
x = int(input("Enter the first number: "))
y = int(input("Enter the second number: "))

print("Addition (x + y): ", (x + y))
print("Subtraction (x - y): ", (x - y))
print("Multiplication (x * y): ", ( x * y))

print("Division (x / y): ", (x / y ))
print("Floor division (x // y): ", (x // y))

print("Modulus (x % y): ", (x % y))
print("Exponential (x ** y): ", (x ** y))

```

    Enter the first number:  23
    Enter the second number:  45


    Addition (x + y):  68
    Subtraction (x - y):  -22
    Multiplication (x * y):  1035
    Division (x / y):  0.5111111111111111
    Floor division (x // y):  0
    Modulus (x % y):  23
    Exponential (x ** y):  18956258430116202791319715713277227626159289499745290235663543



```python

```


---
**Score: 20**