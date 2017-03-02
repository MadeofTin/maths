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

There are two operations that deal directly with manipulating numbers. Both are non communicative and represent the practical inverses of each other.

### Folding

Folding a number is like taking a piece of paper and folding it. The instruction informs the operator the number of folds made in that paper. This means that folding something once would be equivilent to dividing it in half. Folding by 0 would be like giving someone a piece of paper, asking them to fold it 0 times, and then return it to you. It returns the number again with no change.

#### Example in Python

```python

def fold(number, instruction):

  # In division folding is equivilent too
  number = number / (instruction + 1)
  
  return number
```



### Expanding

Expanding is like taking a foldable fence and pulling out as many sections from the stack you require. Because this is an abstract concept you have an infinite stack from which to pull. The resulting number is the sum total of "fence" parts pulled out. Pulling out one fence piece would result in doubling the value. Pulling out 2 would result in tripling the initial value. This is because, depending on your point of view, you either start with a fence piece, or when you end you still have the fence piece you began with. Expanding 0 times leaves the stack alone and returns the number with no change.

#### Visual Representation
![Four Expanding Once] [expanding-4]

#### Example in Python

```python

def expand(number , instruction):

  # In Multiplication expanding is equivlent too
  number = number * (instruction + 1)
  
  return number

```

[expanding-4]: https://docs.google.com/drawings/d/16MxhyjLn1j1CuEi2yjMiKZs3FoGknmxsJO7prQyxork/pub?w=425&h=175
