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

`futils` is a collection of Python libraries made with an emphasis in providing constructive type safety and in using parametric polymorphisms. Its aim is to provide universal and extensible functions.

# Structure

# Approach

We adopt a functional/procedural approach. This means that we rarely use classes/methods, and never use objects directly. When defined, classes are endowed with static methods in order to create namespaces inside modules instead of to work as a blueprint for objects.

> Our primary focus is on functions.


We begin by redefining, generalizing and unifying the basic builtin Python operations/methods, which are then used in the construction of additional functions. 
 

> In sum, `futils` is about:
> 1. functions
> 2. unification (parametric polymorphisms)
> 3. type safety (through [safe](ximenesyuri/safe))
> 4. simplicity  

> For more details about `futils` philosophy, see [doc/phi](./doc/phi.md)

A functional approach to Python, with an emphasis in type safety and parametric polymorphisms.
