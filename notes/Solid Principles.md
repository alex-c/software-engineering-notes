---
tags: [OOP]
title: Solid Principles
created: '2020-02-24T17:08:43.874Z'
modified: '2020-02-24T17:26:25.041Z'
---

# Solid Principles

The [SOLID principles](https://en.wikipedia.org/wiki/SOLID) of object-oriented programming are:

- **Single responsibility principle**: A class should only have a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the class.
- **Open–closed principle**: Software entities should be open for extension, but closed for modification.
- **Liskov substitution principle**: Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.
- **Interface segregation principle**: Many client-specific interfaces are better than one general-purpose interface.
- **Dependency inversion principle**: One should depend upon abstractions, not concretions.

## Single Responsibility Principle

The [single responsibility principle](https://en.wikipedia.org/wiki/Single_responsibility_principle) is a computer programming principle that states that every module or class should have responsibility over a single part of the functionality provided by the software, and that responsibility should be entirely encapsulated by the class, module or function. All its services should be narrowly aligned with that responsibility.

## Open-Closed Principle

The [open/closed principle](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle) states "*software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification*"; that is, such an entity can allow its behaviour to be extended without modifying its source code. 

## Liskov Substitution Principle

The [Liskov substitute principle](https://en.wikipedia.org/wiki/Liskov_substitution_principle) states that in a computer program, if `S` is a subtype of `T`, then objects of type `T` may be replaced with objects of type `S` without altering any of the desirable properties of the program (correctness, task performed, etc.). More formally, the Liskov substitution principle (LSP) is a particular definition of a subtyping relation, called (strong) behavioral subtyping, that was initially introduced by Barbara Liskov in a 1987 conference keynote address titled "Data abstraction and hierarchy". It is a semantic rather than merely syntactic relation, because it intends to guarantee semantic interoperability of types in a hierarchy, object types in particular. 

## Interface Segregation Principle

The [interface segregation principle](https://en.wikipedia.org/wiki/Interface_segregation_principle) (ISP) states that no client should be forced to depend on methods it does not use. ISP splits interfaces that are very large into smaller and more specific ones so that clients will only have to know about the methods that are of interest to them. Such shrunken interfaces are also called role interfaces. ISP is intended to keep a system decoupled and thus easier to refactor, change, and redeploy. 

## Dependency Inversion Principle

In object-oriented design, the [dependency inversion principle](https://en.wikipedia.org/wiki/Dependency_inversion_principle) is a specific form of decoupling software modules. When following this principle, the conventional dependency relationships established from high-level, policy-setting modules to low-level, dependency modules are reversed, thus rendering high-level modules independent of the low-level module implementation details. The principle states:

- High-level modules should not depend on low-level modules. Both should depend on abstractions (e.g. interfaces).
- Abstractions should not depend on details. Details (concrete implementations) should depend on abstractions.

By dictating that both high-level and low-level objects must depend on the same abstraction, this design principle inverts the way some people may think about object-oriented programming.
