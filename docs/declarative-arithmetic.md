# Declarative Arithmetic

#### Introduction

Declarative Arithmetic is an alternative to General Arithmetic used for manipulating numbers. It is a more strict form of arithmetic that declares explicitly in the operations themselves which value is the number being manipulated and which value is the instruction used in the operation. The most notable side effect of this is that the operations are not commutative.

A general example in python
```python

def operator(number , instruction):

  ### Manipulate the number directly according
  ### to the value of the instruction
  
  Return number
```

If both arguments to the operator are numbers then the operation itself is considered sutible instructions for the operator. This is the case with addition.

### The Operations

There are two operations that deal directly with manipulating numbers. Both are non communicative and represent the practicle inverses of each other.

### Folding

![Folding Four Once] [folding-4]

### Expanding






[folding-4]: https://docs.google.com/drawings/d/1zVTf3UrXcptXrio7-9IqjeoF0tMAQXgx1sxyAiP7Uu0/pub?w=428&h=165
