---
tags: [Programming Paradigms]
title: Functional Programming
created: '2020-02-24T17:27:02.198Z'
modified: '2020-03-16T11:17:42.915Z'
---

# Functional Programming

## First-Class and Higher-Order Functions

### Higher-Order Functions

[Higher-order functions](https://en.wikipedia.org/wiki/Higher-order_function) are functions that can either take other functions as arguments or return them as results. In calculus, an example of a higher-order function is the differential operator `d/dx`, which returns the derivative of a function `f`. 

### First-Class Functions

A programming language is said to have [first-class functions](https://en.wikipedia.org/wiki/Functional_programming#First-class_and_higher-order_functions) if it treats functions as first-class citizens. This means the language supports passing functions as arguments to other functions, returning them as the values from other functions, and assigning them to variables or storing them in data structures.

## Pure Functions

Pure functions (or expressions) have no side effects (memory or I/O).

## Recursion

Iteration (looping) in functional languages is usually accomplished via recursion. Recursive functions invoke themselves, letting an operation be repeated until it reaches the base case. Although some recursion requires maintaining a stack, tail recursion can be recognized and optimized by a compiler into the same code used to implement iteration in imperative languages.

## Evaluation Strategy

Functional languages can be categorized by whether they use strict (eager) or non-strict (lazy) evaluation, concepts that refer to how function arguments are processed when an expression is being evaluated. The technical difference is in the denotational semantics of expressions containing failing or divergent computations. Under strict evaluation, the evaluation of any term containing a failing subterm fails. For example, the expression:

```
print length([2+1, 3*2, 1/0, 5-4])
```

fails under strict evaluation because of the division by zero in the third element of the list. Under lazy evaluation, the length function returns the value 4 (i.e., the number of items in the list), since evaluating it does not attempt to evaluate the terms making up the list. In brief, strict evaluation always fully evaluates function arguments before invoking the function. Lazy evaluation does not evaluate function arguments unless their values are required to evaluate the function call itself. 

## Referential Transparency

Functional programs do not have assignment statements, that is, the value of a variable in a functional program never changes once defined. This eliminates any chances of side effects because any variable can be replaced with its actual value at any point of execution. So, functional programs are referentially transparent.
