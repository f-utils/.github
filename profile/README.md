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

`f-utils` is a collection of Python libraries aiming to provide universal and extensible functions based on the core Python utilities. 

# Approach

We adopt a functional/procedural approach. This means that we rarely use classes/methods, and never use objects directly. When defined, classes are endowed with static methods in order to create namespaces inside modules instead of to work as a blueprint for objects. 

Furthermore, we strongly adopt parametric polymorphisms. Thus, to us, functions should have a unified scope, serving to multiple types. Since Python is dynamically typed, this could creates the perfect environment to naive type errors. However, our parametric polymorphism (and, actually, all functions) are built following a custom systematics which ensures type safety.

> `f-utils` is about:
> 1. functions
> 2. unification
> 3. type safety
> 4. minimalism

# Structure
