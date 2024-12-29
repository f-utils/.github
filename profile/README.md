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

- website: [futils.org](https://futils.org)
- contact: [futils@gmx.ie](mailto:futils@gmx.ie)

# Approach

We adopt a `functional` and `procedural` approach. This means that we rarely use classes/methods, and never use objects directly. When defined, classes are endowed with static or class methods, so that instead of working as blueprint for objects, they are used to create namespaces inside modules or to establishes shared data between modules.

Furthermore, we strongly adopt `parametric polymorphisms`. Thus, to us, functions should have a unified scope, serving to multiple types. Since Python is dynamically typed, this could creates the perfect environment to naive type errors. However, our parametric polymorphism (and, actually, all functions) are built following a custom systematics which ensures `type safety`.

# Principles

`f-utils` is built keeping in mind the following first principles:
1. `function-first`: functions are the main entities
2. `structural minimalism`: dependencies should be minimal and, while introduced, must be hardly justified
3. `constructivism`: define primitive entities and derive anything from them
4. `unification`: a concept should have a single representative

# Structure

The `f-utils` libraries appears into two kinds: 
1. `core`: to be imported outside a namespace
2. `libs`: to be imported in some namespace.

The `core` libraries contains the `f-utils` systematics and its primitive functions:
1. [f](https://github.com/f-utils/f): where our type safety systematics is implemented, which is the kernel of each lib
2. [f-core](https://gitub.com/f-utils/f-core): with the `f-utils` primitive functions

The `libs` libraries contains context-based functions, which are built using the primitive functions:
1. [f-json](https://github.com/f-utils/f-json): focused on manipulating `json` data
2. [f-re](https://github.com/f-utils/f-re): dealing with regex
3. [f-path](https://github.com/f-utils/f-path): operations involving paths
4. [f-http](https://github.com/f-utils/f-path): concerning http requests
5. and so on.

# Documentation

The project-level documentations are in [f-utils/general/docs](https://github.com/f-utils/general/docs):
1. [philosophy](https://github.com/f-utils/general/docs/philosophy.md): discussing aspects of `f-utils` philosophy and principles
2. [systematics](https://github.com/f-utils/general/docs/systematics.md): on `f-utils` systematics, used to build parametric polymorphisms satisfying constructive type safety
3. [standards](https://github.com/f-utils/general/docs/standards.md): about `f-utils` structure and development standards
3. [contributing](https://github.com/f-utils/general/docs/contributing.md): describing the details on how to contribute to the project
5. and so on.

Each lib contains its `reference manual` and `user manual`, allocated in its own repository:
1. `f-lib/doc/user.md`: the user manual of lib `f-lib`
2. `f-lib/doc/ref.md`: the reference manual of lib `f-lib`

The documentations can also be accessed directly from our website: [futils.org](https://futils.org).

# Interacting

Interactions and contributions are most welcome!

1. General suggestions, questions, feature or lib request, and any other kind of interaction should be made through issues in the [f-utils/general](https://github.com/f-utils/general) repository.
2. Lib specific issues should also be created in [f-utils/general](https://github.com/f-utils/general), while pull requests should be created in the specific directory. See [contributing](https://github.com/f-utils/general/docs/contributing.md) for more details.

We also maintain a Discord server. An invite link can be found [here](https://discord.gg/TUCrADNt).

 
