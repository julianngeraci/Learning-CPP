# C++ Fundamentals and Object-Oriented Programming

This repository contains C++ source code files that demonstrate core language features, including object-oriented programming (OOP), memory management, function passing, and standard containers. It is organized to support learning and experimentation with both basic and intermediate concepts in C++.

## Folder Structure and File Overview

The code is grouped conceptually by topic. Each section typically includes `.cpp` implementation files, corresponding `.hpp` header files, and `*_main.cpp` files that demonstrate usage.

### Object-Oriented Programming

- **Classes**
  - `classes.cpp`, `classes.hpp`, `classes_main.cpp`: Basic class definition and usage.
- **Constructors**
  - `constructors.cpp`, `constructors.hpp`, `constructors_main.cpp`: Demonstrates default, parameterized, and copy constructors.
- **Destructor**
  - `destructor.cpp`, `destructor.hpp`, `destructor_main.cpp`: Explores resource cleanup and object destruction.

### C++ Language Features

- `conditionals.cpp`: If-statements, switch cases, and other conditional logic.
- `loops.cpp`: Usage of `for`, `while`, and `do-while` loops.
- `logicalops.cpp`: Demonstration of logical operators (`&&`, `||`, `!`).
- `variables.cpp`: Declaration and scope of variables.

### Functions and Parameter Passing

- `functions.cpp`, `functions2.cpp`: Function declarations, overloading, and usage.
- `pass-by-reference.cpp`, `pass-by-reference-const.cpp`: Different parameter-passing mechanisms.
- `references.cpp`: Reference variables and their behavior.

### Memory and Pointers

- `pointers.cpp`: Basics of pointer syntax and dereferencing.
- `dereference.cpp`: Detailed look at pointer dereferencing.
- `memory.cpp`: Dynamic memory allocation with `new`/`delete`.

### Standard Containers

- `vectors.cpp`: Introduction to the `std::vector` container.

## Getting Started

To compile and run individual examples:

```bash
g++ -std=c++17 -o classes_main classes.cpp classes_main.cpp
./classes_main
