# Hydrotron Lang (CPP Compiler)

This compiler is written in C++ but hopefully it will get to a point where it can be self-hosted.

## Building

Requires `nasm` and `ld` on a Linux operating system.

```bash
git clone https://github.com/NDamwani/hydrotron-compiler.git
cd hydrogen-cpp
mkdir build
cmake -S . -B build
cmake --build build
```

Executable will be `hydro` in the `build/` directory.

