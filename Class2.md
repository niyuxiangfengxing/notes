# Class 2

## 1. Operands

The operands in Python is different from those in calculator

* $\times$  -> *
* ^ -> **
* mod -> %
* \+ -> +
* \- -> -

And by typing the statement `2^1000`, we can know that there exists automatic type conversion from integer type to long number type. 

## 2. Module

We can import existing modules like `math` to make life easy. For example

```python
from math import sqrt

print(sqrt(9))
```

Also, we could define our own module. Say open one new file named `my_module.py`, and define some functions in it like this.

```python
def my_welcome():
    print("Hello there")
```

Then in another python file in the same directory, we can import it and use the functions in it.

```python
from my_module import my_welcome

my_welcome()
```

With the help of module, we can reuse existing code and test it more conveniently. 

## 3. Errors

syntax error

runtime error