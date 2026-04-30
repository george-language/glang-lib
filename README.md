# `glang-lib`
This repository contains the entire core and standard libraries used in GLang.

- `src/core`: **GLang's core library.**
- `src/std`: **GLang's standard library.**

## About
The `core` library is a set of functions and constants (e.g. `add`) for GLang. All programs use the `core` library (imported automatically)

The `std_*` libraries are built on top of the `core` library. They use fundamental functions provided by the `core` library (e.g. `add`) to create modules like `std_os` or `std_hashmap`.
