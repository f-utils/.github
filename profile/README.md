```
  /$$$$$$                  /$$     /$$ /$$          
 /$$__  $$                | $$    |__/| $$          
| $$  \__/     /$$   /$$ /$$$$$$   /$$| $$  /$$$$$$$
| $$$$ /$$$$$$| $$  | $$|_  $$_/  | $$| $$ /$$_____/
| $$_/|______/| $$  | $$  | $$    | $$| $$|  $$$$$$ 
| $$          | $$  | $$  | $$ /$$| $$| $$ \____  $$
| $$          |  $$$$$$/  |  $$$$/| $$| $$ /$$$$$$$/
|__/           \______/    \___/  |__/|__/|_______/ 
```

# About 

`f-utils` is a collection of Python libraries aiming to provide universal and extensible functions that implements the core Python utilities. 

## Approach

We adopt a *functional* and *procedural* approach. This means that we rarely use classes/methods, and never use objects directly. When defined, classes are endowed with static or class methods, so that instead of working as blueprint for objects, they are used to create namespaces inside modules or to establishes shared data between modules. 

Furthermore, we strongly adopt *parametric polymorphisms*. Thus, to us, functions should have a unified scope, serving to multiple types. Since Python is dynamically typed, this could creates the perfect environment to naive type errors. However, our parametric polymorphism (and, actually, all functions) are built following a custom systematics which ensures *type safety*.

## Dependencies

`f-utils` is intended to be *minimal*: the core should not have any dependency and, while introduced in additional libs, they must be hardly justified. Internally, the interdependence should be mostly linear, avoiding cyclic imports as possible.

## Intuition

The `f-utils` structure and its interface with the user are designed to be *intuitive* and *informative*: few functions with a clear meaning and standardized names. Also, the complete information of each function should be quickly accessible in a human readable format. 

## Summary

In sum, `f-utils` is about the following principles:
1. functions first
2. unification
3. type safety
4. minimalism
5. constructivism

For more on `f-utils` philosophy, execute `info philosophy` at [<futils-domain>](https://).

# Structure

The `f-utils` libraries appears into two kinds: 
1. `core`: to be imported outside a namespace
2. `libs`: to be imported in some namespace.

The `core` libraries contains the `f-utils` systematics and its primitive functions:
1. [f](https://github.com/f-utils/f): where our type safety systematics is implemented, which is the kernel of each lib
2. [f-core](https://gitub.com/f-utils/f-core): with the `f-utils` primitive functions

The `libs` libraries contains context-based functions, which are built using the primitive functions.

# Interacting

Interactions with the project are most welcome.

## General

1. General suggestions, questions, feature or lib request, and any other kind of interaction should be made through issues in the [f-utils/general](https://github.com/f-utils/general) repository.
2. Lib specific issues should be open in the corresponding repository. 

## Contributing

...
