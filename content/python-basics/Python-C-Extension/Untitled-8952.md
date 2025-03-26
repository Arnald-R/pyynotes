---
title: Untitled-8952
date: 2025-03-26
author: Your Name
cell_count: 7
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/8.-coroutines
```


```python
import hello
hello.hello_world()  # Output: Hello, World!


```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    Cell In[2], line 1
    ----> 1 import hello
          2 hello.hello_world()  # Output: Hello, World!


    ModuleNotFoundError: No module named 'hello'



```python
# doubt
```


```python
#include <Python.h>

static PyObject* hello_world(PyObject* self, PyObject* args) {
    printf("Hello, World!\n");
    Py_RETURN_NONE;
}

static PyMethodDef HelloMethods[] = {
    {"hello_world", hello_world, METH_VARARGS, "Prints Hello, World!"},
    {NULL, NULL, 0, NULL}
};

static struct PyModuleDef hellomodule = {
    PyModuleDef_HEAD_INIT,
    "hello",
    NULL,
    -1,
    HelloMethods
};

PyMODINIT_FUNC PyInit_hello(void) {
    return PyModule_Create(&hellomodule);
}
```


      Cell In[3], line 3
        static PyObject* hello_world(PyObject* self, PyObject* args) {
               ^
    SyntaxError: invalid syntax




```python

```


```python

```


---
**Score: 5**