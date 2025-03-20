---
title: Global-Variable
date: 2025-03-20
author: Your Name
cell_count: 12
score: 10
---

```python
#global-variable
```


```python
x = 20
def my_function():
    print("inside function:",x)
my_function()
print("outside function:",x)
```

    inside function: 20
    outside function: 20



```python
#local variable
```


```python
x = 100
def mynew_function():
    x = 20 * 20
    print("the inside function:",x)
mynew_function()
print("outside function:",x)
```

    the inside function: 400
    outside function: 100



```python
name = "aren"
def my_func():
    global name
    name = "Arnald"
    print("inside the function:",name)
def my_func1():
    print("inside the another function:",name)
my_func()
my_func1()
print("outside the function:",name)
```

    inside the function: Arnald
    inside the another function: Arnald
    outside the function: Arnald



```python
city = 'New York' # a global variable.
def my_function1():
    global city
    city = 'los angels'
    print("Inside my_function1: ", city)
def my_function2():
    global city
    city = 'Sydney'
    print("Inside my_function2: ",city)

# Calling the function.
my_function1()
my_function2()
print("Outside function: ", city)

```

    Inside my_function1:  los angels
    Inside my_function2:  Sydney
    Outside function:  Sydney



```python
#local variable
```


```python
def my_func():
    city = 'coimbatore'
    print(city)
# Calling the function.
my_func()
print(city)

```

    coimbatore
    Sydney



```python
# Declare a global variable and assign it a value.
message1 = "This is a global variable, and we can access it anywhere in the program."
# Create a function named display.
def display():
# Declare a local variable and assign it a value.
    message2 = "This is a local variable, and we can access it only inside the function body."
    print(message2) # Accessing local variable from inside the function.

print(message1); # Accessing the global variable.
display() # Calling function.

```

    This is a global variable, and we can access it anywhere in the program.
    This is a local variable, and we can access it only inside the function body.



```python
# Declare global variables.
student1 = "John"
student2 = "Larry"

# Create a function named showMe.
def showMe():
    student2 = "Harry" # Here, local variable is sharing the same name as global variable.
    student3 = "Deep"
    print(student2, " ",student3)

showMe(); # calling function.
print(student1, " ", student2)

```

    Harry   Deep
    John   Larry



```python

```


```python

```


---
**Score: 10**