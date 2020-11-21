---
marp: true
_class: lead
paginate: true
backgroundColor: #fff
# backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---

![bg left:50% 60%](https://i.imgur.com/RvHqB9S.png)

# **Chapter 2**

## Variables and arithmetic

---
# Code Structure

Like many other programming languages, it is very important to pay close attention to the **structure** of your code when writing.

Structure largely refers to "syntax" used, which includes specific characters, spaces, tabs to convey exactly the operations python needs to perform. 

For exmaple:

```python
# This is a function calculates 1 + 2 + ... + n
#   using the formula sum = n(n+1)/2
def add_numbers(n):
  """Return 1 + 2 + ... + n."""
  return n * (n+1)//2   # The // operator means integer division
```

---

# Reserved Words

There are a certain set of words that python **reserves** for itself. When python sees these keywords it runs specific predefined functions.

For example:

- `import` tells python to bring in code that has been written in a different file
- `def` defines a function that can be used elsewhere
- `while` instructes python to repeat code over and over while a condition is true

Some Keywords in python:
```python
import, from, def, return, None, while, break, continue, pass, True, False, elif, and, not
```

---

# IDLE

