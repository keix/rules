# The Rules of Programming - Fixed Examples

This repo contains all the source examples from the book The Rules of Programming, with fixes to make them compile successfully.

## Compilation Status

All examples in this repository have been updated to compile without errors. The following fixes were applied:
- Fixed 32-bit vs 64-bit integer issues
- Added missing `typename` keywords for template code
- Included necessary headers (e.g., `<string>`)
- Fixed various syntax errors and warnings

## Building the Examples

### Prerequisites
- Make (for building all examples at once)
- C++ compiler (tested with clang++ 19.x)

### Compiling Individual Examples

You can compile any individual rule example using your C++ compiler:

```bash
# Compile rule1 with dependencies
clang++ -std=c++17 main.cpp tests.cpp rule1.cpp -o rule1
```

### Building All Examples with Make

A Makefile is provided to build all examples at once:

```bash
make
./rules    # to run the compiled executable
make clean # to remove compiled binaries
```

This will compile all `.cpp` files and link them into a single executable called `rules`.


