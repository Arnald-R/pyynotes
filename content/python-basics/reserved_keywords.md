---
title: Reserved Keywords
date: 2025-03-26
author: Your Name
cell_count: 45
score: 45
---

```python
#created at 20250118
```


```python
https://www.scientecheasy.com/2022/09/reserved-keywords-in-python.html/

```


```python
#Reserved keywords
```


```python
#True and False
```


```python
print( 1==1)
print( 15>16 )
print( True or False )
print( 10>=8 )
```

    True
    False
    True
    True



```python
print(20<12)
print(5<=3)
print(False == 0)
print(False == 1)
print(False + False + 1)
```

    False
    False
    True
    False
    1



```python
#None Keyword
```


```python
print(None == False)
print( None == 0 )
print( None == " " )
```

    False
    False
    False



```python
#true 
```


```python
print(True or True)
print(False or False or True)
print(True or False)
print(True or 1)
```

    True
    True
    True
    True



```python
num = [10, 25, 30, 40, 50]
print(50 in num)
print(15 in num)
```

    True
    False



```python
#keyword is to traverse over a sequence in a for loop
```


```python
for i in 'Arnald':
    print(i)
```

    A
    r
    n
    a
    l
    d



```python
#if both objects are same means is true
print( True is True )
print( False is True )
print( None is None )
print((2 + 4) is (3 * 2))
```

    True
    False
    True
    True


    <>:5: SyntaxWarning: "is" with 'int' literal. Did you mean "=="?
    <>:5: SyntaxWarning: "is" with 'int' literal. Did you mean "=="?
    /tmp/ipykernel_7250/2494937313.py:5: SyntaxWarning: "is" with 'int' literal. Did you mean "=="?
      print((2 + 4) is (3 * 2))



```python
print( [ ] == [ ] )
print( [ ] is [ ] )  
print( { } == { } )
print( { } is { } )
```

    True
    False
    True
    False



```python
#Iteration Keywords – for, while, break, continue
```


```python
for count in range(1,4):
    print("Hi,Arnald R")
```

    Hi,Arnald R
    Hi,Arnald R
    Hi,Arnald R



```python
c=0
while(c<3):
    print("the count is:",c)
    c=c+1
print("while loop ended")
    
```

    the count is: 0
    the count is: 1
    the count is: 2
    while loop ended



```python
for i in range(1,5):
    if i == 3:
        break
    print(i)
```

    1
    2

 

```python
for i in range(1,5):
    if i == 3:
        continue
    print(i)
```

    1
    2
    4



```python
#Conditional keywords – if, else, and elif

```


```python
i = 10
if (i == 5):
    print ("Hello")
elif (i == 10):
    print ("Python keywords")
else:
    print ("Hello Python")
```

    Python keywords



```python
#def keyword
```


```python
def func():
    print("method")
func()
```

    method



```python
#Return Keywords – Return, and Yield
```


```python
def fun_key():
    x=20
    return x
def fun_no_key():
    y=50
print(fun_key())
print(fun_no_key())
```

    20
    None



```python
#yield
```


```python
def func():
    x = 0
    for i in range(5):
        x += i
        yield x
for i in func():
    print(i)
```

    0
    1
    3
    6
    10



```python
#with keyword
```


```python
with open('myfile.txt','w') as file:
    file.write('Hi,Arnald')
```


```python
#as keyword
```


```python
import math as x
print(x.cos(0))
```

    1.0



```python
# Lambda keyword
cube = lambda x: x * x * x
print(cube(7))
```

    343



```python
import math
print(math.sqrt(4))
```

    2.0



```python
from math import sqrt
print(sqrt(625))
```

    25.0



```python
my_var1 = 200
my_var2 = "Scientech Easy"

# check if my_var1 and my_var2 exists.
print(my_var1)
print(my_var2)

# delete both the variables.
del my_var1
del my_var2

# check if my_var1 and my_var2 exists
print(my_var1)
print(my_var2)

```

    200
    Scientech Easy



    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[45], line 13
         10 del my_var2
         12 # check if my_var1 and my_var2 exists
    ---> 13 print(my_var1)
         14 print(my_var2)


    NameError: name 'my_var1' is not defined



```python
g_var = 50
def func_read():
    print(g_var)
def func_write():
    global g_var
    g_var = 100

func_read()
func_write()
func_read()

```

    50
    100



```python
def outer_func():
    x = 50
    def inner_func():
        nonlocal x
        x = 100
        print("Inner function: ",x)
    inner_func()
    print("Outer function: ",x)

outer_func()

```

    Inner function:  100
    Outer function:  100



```python
def outer_func():
    x = 50
    def inner_func():
        x = 100
        print("Inner function: ",x)
    inner_func()
    print("Outer function: ",x)

outer_func()

```

    Inner function:  100
    Outer function:  50



```python
#Exception Handling Keywords – try, except, raise, and finally
```


```python
# initializing the value of variables.
x = 10
y = 0
# No exception raised in try block
try:
    z = x // y  # raises divide by zero exception.
    print(z)
# handles zero division exception
except ZeroDivisionError:
    print("Cannot divide by zero")

finally:
    # this block always gets executed regardless of exception produced.
    print('finally block always gets executed')

```

    Cannot divide by zero
    finally block always gets executed



```python
#assert
```


```python
x = 10
assert x >= 10
assert x < 10
x = 10
assert x < 10, "x is not less than 10"



```


    ---------------------------------------------------------------------------

    AssertionError                            Traceback (most recent call last)

    Cell In[55], line 3
          1 x = 10
          2 assert x >= 10
    ----> 3 assert x < 10
          4 x = 10
          5 assert x < 10, "x is not less than 10"


    AssertionError: 



```python

```


---
**Score: 45**