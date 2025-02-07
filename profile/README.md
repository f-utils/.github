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

`f-utils` is a Python framework designed to provide type safety and universal constructions. 

- website: [futils.org](https://futils.org)
- contact: [futils@gmx.ie](mailto:futils@gmx.ie)
- discord: [coolab](https://discord.gg/waANUyCUGE)

# Principles

`f-utils` is built keeping in mind the following principles:
1. `function-first`: functions are the main entities
2. `minimalism`: dependencies should be minimal and, while introduced, hardly justified
3. `constructivism`: define primitive entities and derive anything from them
5. `universality`: few operations for multiple types

# Structure

The framework consists on the four layers:
1. `primitive`: minimal structure to develop with `f-utils` 
2. `primary`: primary libraries
3. `helper`: additional libraries
4. `derived`: libraries derived from the others

```
primitive layer
--------------------
lib           scope
-----------------------------------------------
f             constructs f-utils systematics
f-core        builds primitive f-utils entities
f-tools       provides f-utils dev tools
```

```
helper
--------------------
lib           scope
-----------------------------------------------
f-monad       implements some helper monads
f-plus        provides a lot of derived entities
```

```
primary
--------------------
lib           scope
-----------------------------------------------
f-ansi        deals with ANSI code
f-log         deals with log services
f-path        deals with path-like entities
f-json        deals with json entities
f-re          deals with regex and patterns
...
```

# Documentation

See [f-utils/general/docs](https://github.com/f-utils/general/blob/main/docs) or try `$ docs <something>` in [futils.org](https://futils.org).

# Interacting

Interactions and contributions are most welcome!

1. General suggestions, questions, feature or lib request, and so on, should corresponds to issues in the [f-utils/general](https://github.com/f-utils/general) repository.
2. Lib specific issues should also be created in [f-utils/general](https://github.com/f-utils/general), while pull requests should be created in the specific directory. See [contributing](https://github.com/f-utils/general/docs/contributing.md) for more details.
