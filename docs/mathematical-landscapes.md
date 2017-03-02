
# Mathematical Landscapes

#### Introduction

One day I was listening on the radio to a discussion about the traveling salesmen problem. As I was thinking about it I imagined a raindrop falling on top of a mountain range navigating its' way to the very bottom. In this case the raindrop is following the easiest path, but it has no need to calculate that path in advance. Wherever it is, it goes down until it can no longer go down.

I then wondered if you first built a Mathematical Landscape, perhaps you could traverse that from the point of view from the raindrop. At each step you find yourself, go down, until you can't go down further.

## A Graph with N Points

![Graph of Points] [Graph-1]

## Construct the Chains

From each point order the other points based on distance from that point.

![Chain from A] [Graph-2]


| Point | 1st | 2nd | 3rd | 4th | 
| ---   | ----| --- | --- | --- |
| **A**     | B | C | E | D |
| **B**     | C | A | E | D |
| **C**     | B | E | D | A |
| **D**     | E | C | B | A |
| **E**     | C | D | B | A |

## Combine the Chains

For each point, take is position and the postion of the other point relative to it and combine them using the Expand Operator.

![Combine Chains] [Graph-3]

A <-> E = 3..4 = 15

```python
#Expansion Represented in Multiplication
3..4 = 3*(4+1)
```

| Point | A         | B         | C         | D         | E         |
| ---   | ---       | ---       | ---       | ---       | ---       |
| **A** | -         | 1..2 = 3  | 2..4 = 10 | 4..4 = 20 | 3..4 = 15 |
| **B** | 2..1 = 4  | -         | 1..1 = 2  | 4..3 = 16 | 3..3 = 12 |
| **C** | 4..2 = 12 | 1..1 = 2  | -         | 3..2 = 9  | 2..1 = 4  |
| **D** | 4..4 = 20 | 3..4 = 15 | 2..3 = 8  | -         | 1..2 = 3  |
| **E** | 4..3 = 16 | 3..3 = 12 | 1..2 = 3  | 2..1 = 4  |  -        |


[Graph-1]: https://docs.google.com/drawings/d/1eqBASrvcI3p8bWkxX62QI9QNZ--CXPLZohplyegMQo8/pub?w=220&h=149
[Graph-2]: https://docs.google.com/drawings/d/1aOZBCW15eupqPKkuJxA7iqWJsokTK1_-Luhity9dDV4/pub?w=220&h=149
[Graph-3]: https://docs.google.com/drawings/d/13PD5ItRpvo1uiU8BC0dfGAZpJaEdPprnrR8jLjRst8Q/pub?w=220&h=149
