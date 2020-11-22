---
marp: true
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---

# Discrete Math with Python

## How computers work, and a brief introduction to python

---
# How a computer works

Everything the computer does revolves around two core components: CPU and Memory

## CPU

The center of everything is the **C**entral **P**rocessing **U**nit. Essentially it's a piece of silicon with trillions of switches baked into it. Each switch controls the flow of electricity through the CPU. The faster a processor can operate (Ghz), the faster it can "flip" the switches. Everything is based on whether the switch is on `1` or off `0`.

## Memory

Memory is a series of storage units which can hold 8bits (1 byte) each. A bit is a `0` or a `1`. The CPU can access the memory by referring to an address.

---

# How a computer works

## Programming

There are numerous programming languages that provide varying access to the CPU.

One of the "closest" languages to the CPU is called Assembly. It allows you to use names to refer to specific CPU functions and memory addresses.

We will use python, a language that is far removed from the actual instructions required by the CPU. When we type `print("hello")`, there is a lot of code we are running that we never see.

---

# Python

Fun fact: python was named after Monty Python

There are two ways to run code for a CPU: Compiling and Interpreting

1. Compiling will take **all of your code** and translate it to code that is better understood by a CPU
2. Interpreting runs your code **line by line** as needed

Python is a hybrid of these two. It compiles your code first, then runs the compiled code when needed.

The benefit of this is that we can use a python interpreter to test our code before it runs.

---

# Python Interpreter

We can use a python interpreter to help "play" around with python without needing to create a file and compile it.

In Repl.it, we can see the interpreter in the black window on the right side of the page. This is commonly referred to as the "shell".

![](https://i.imgur.com/0aLRd8W.png)

When you install python, the standard interpreter is named IDLE, after Eric Idle of Monty Python.

---

# Python Interpreter

Play around with the interpreter and make a short program. Type the following into the shell:

```python
s = 0
for k in range(1,7):
  s += k
  print(k,s)
```

You should see the output:
```python
1 1
1 2
3 6
4 10
5 15
6 21
```

---

# Python files

We don't write python programs in the interpreter. When we want to write a program, we put it in a text file named `______.py`.

Because it's just a text file, you can use any text editor to write it, but we will normally use an **IDE**, an Integrated Development Environment that helps us as we write our code.

In a Repl.it project, place the same code as before into a python file and hit the run button at the top. What do you see?