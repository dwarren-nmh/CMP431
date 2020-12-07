---
marp: true
_class: lead
paginate: true
backgroundColor: #fff
# backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---

# Functions in Python

---

# Math Functions

A function in math is a tool that accepts an input and provides an output.

Normally a function is only allowed to have one output for each input.

You have traditionally seen functions like this:

$f(x) = 2x + 3$

The function's name is `f`, it accepts the input `x`, and it provides an output `f(x)`.

The *domain* is the possible input values, the *range* is the possible output values.

---

# Python Functions

Python can do something similar to a math function:

The following is similar to the algebraic syntax of: $f(x) = 2x + 3$ :

```python
def f(x):
  return 2 * x + 3
```

- The domain of the function, `x`, is the argument for the function, aka the parameter
- The range of the function is the `return` statement

---

# Python Functions

Different from math, a function in python can accept anything and return anything, or nothing.

A function can:

- Take one or more arguments
- Take no arguments
- Return one or more values
- Return no values
- Return a different value with the same input

---

# Python Functions - more than one input

```python
from math import sqrt

def distance(x1, y1, x2, y2):
  """returns the distance between two coordinates"""
  return sqrt((x2 - x1)**2 - (y2-y1)**2)

print(distance(0, 3, 4, 0))
```

The above will return a float of `5.0`

---

# Python Functions - no input

```python
def print_hello():
  print("hello")

print_hello()
```

---

# Python Functions - No return

This example accepts a list, modifies it, but never returns it.

```python
def rotate(items):
  items.append(items.pop(0))

nums = [1,2,3,4]
print(nums) # --> [1,2,3,4]

rotate(nums)
print(nums) # --> [2,3,4,1]
```

---

# Python Functions - Different Returns

A good example of a function that may provide a different return is the `randint` function from the random module

This example will return a random number from 1 to 6, inclusive, each time. It might be the same, it might be different, but the inputs are always the same.

```python
from random import randint

print(randint(1,6))
print(randint(1,6))
print(randint(1,6))
print(randint(1,6))
```

---

# Challenge - Heron's Formula Calculator

Create a function that accepts three parameters representing the sides of a triangle. Return the area of the triangle and print it to the shell.

https://i.imgur.com/ThUFIYm.png