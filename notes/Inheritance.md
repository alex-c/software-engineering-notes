---
tags: [OOP ~ Object-Oriented Programming]
title: Inheritance
created: '2020-02-24T17:13:00.935Z'
modified: '2020-02-29T12:38:19.941Z'
---

# Inheritance

In object-oriented programming, inheritance is the mechanism of basing an object or class upon another object (prototype-based inheritance) or class (class-based inheritance), retaining similar implementation. Also defined as deriving new classes (sub classes) from existing ones (super class or base class) and forming them into a hierarchy of classes.

## Class-Based Inheritance

In class-based programming inheritance occurs via defining classes of objects, instead of inheritance occurring via the objects alone. The structure and behavior of an object are defined by a class, which is a definition, or blueprint, of all objects of a specific type. An object must be explicitly created based on a class and an object thus created is considered to be an instance of that class. Inheritance is done by defining new classes as extensions of existing classes: the existing class is the parent class and the new class is the child class. If a child class has only one parent class, this is known as single inheritance, while if a child class can have more than one parent class, this is known as multiple inheritance. This organizes classes into a hierarchy.

## Prototype-Based Inheritance

Prototype-based programming is a style of object-oriented programming in which behaviour reuse (known as inheritance) is performed via a process of reusing existing objects via delegation that serve as prototypes. Delegation is the language feature that supports prototype-based programming.

Prototype-based programming uses generalized objects, which can then be cloned and extended. Using fruit as an example, a "fruit" object would represent the properties and functionality of fruit in general. A "banana" object would be cloned from the "fruit" object and general properties specific to bananas would be appended. Each individual "banana" object would be cloned from the generic "banana" object. Compare to the class-based paradigm, where a "fruit" class would be extended by a "banana" class. 

Example languages:

- JavaScript
- Lua
