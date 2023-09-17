## dreading
Decorator-like Threads for Python

## Installing
You can install it using the command below:
```shell
pip install git+https://github.com/zetrobt/dreading.git
```
## How to use?
Use it like default Threads, but with decorators:
```python
from dreading import thread, Thread

@thread()
def foo():
    print("bar")
```
