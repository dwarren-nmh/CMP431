---
marp: true
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---

# Chapter 3 - Sets and Functions

---

# Sets

A set is a collection of unique (non-repeating) things. We call the "things" elements. 

By definition, sets don't have repeating elements.

Looking in this class, we can find sets everywhere:
- A set of colors for the whiteboard markers
- A set of students
- A set of tables
- A set of clothing items
- A set of alphabet characters
- A set of computers

---

# Sets

$x \in S$ is read as "x is an element of the set S"

We use curly braces to list the elements of a set. For example: $A = \{1,2,3\}$ says that A is a set which contains the elements $1, 2, 3$.

The order of these elements doesn't matter.

## A set can have:
- A finite number of elements: $A = \{1,2,3\}$
- An infinite number of elements: $A = \Z$ (all integers)
- No numbers: $A = \emptyset$ (empty set)

---

# Sets

## Subsets and more notation

We can also define a set which is a smaller portion of another set. This is a **subset**.

If the set $B$ is made up of some of the elements of the set $A$, then $B$ is a subset of $A$.

We write this as $B \subseteq A$, and we read it as "$B$ is a subset of $A$"

The empty set is a subset of all sets: $\emptyset \subseteq A$

A set is a subset of itself: $A \subseteq A$

---

# Python and sets

Python was built to handle sets well. We can use the `set()` function to declare a set. Beyond that it provides us with functions to manipulate the set.

For example: `names = set("david")` creates a set of Strings for each **unique** letter in my name: `'d','a','v','i'`

If we wanted to add elements to this set, we could call the `add()` method: `names.add("m")`, making the set `'d','a','v','i','m'`