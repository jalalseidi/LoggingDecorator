# Logging Decorator

A Python decorator that logs function calls, arguments, and return values.

## Usage
```python
@logging_decorator
def a_function(*args):
    return sum(args)

a_function(1, 2, 3)
```

## Output
```
You called a_function(1, 2, 3)
It returned: 6
```
