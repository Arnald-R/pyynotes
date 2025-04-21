---
title: Async1
date: 2025-04-21
author: Your Name
cell_count: 5
score: 5
---

```python
#created at 20250131
```


```python

```


```python
#async and await for cuncurrent tasks with asyncio
```


```python
import asyncio
async def say_hello():
    print("Hello , World!")
    await asyncio.sleep(1)
    print("Hello , Bye!")

    
asyncio.run(say_hello())
```


    ---------------------------------------------------------------------------

    RuntimeError                              Traceback (most recent call last)

    Cell In[3], line 8
          4     await asyncio.sleep(1)
          5     print("Hello , Bye!")
    ----> 8 asyncio.run(say_hello())


    File ~/miniconda3/envs/py312/lib/python3.12/asyncio/runners.py:190, in run(main, debug, loop_factory)
        161 """Execute the coroutine and return the result.
        162 
        163 This function runs the passed coroutine, taking care of
       (...)
        186     asyncio.run(main())
        187 """
        188 if events._get_running_loop() is not None:
        189     # fail fast with short traceback
    --> 190     raise RuntimeError(
        191         "asyncio.run() cannot be called from a running event loop")
        193 with Runner(debug=debug, loop_factory=loop_factory) as runner:
        194     return runner.run(main)


    RuntimeError: asyncio.run() cannot be called from a running event loop



```python

```


---
**Score: 5**