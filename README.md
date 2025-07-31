# DSA C++ CP Setup

This is a starter template designed to help you quickly set up a competitive programming (CP) and data structures & algorithms (DSA) workflow using C++.

## Features

* Pre-configured `devcontainer` environment for consistent setup
* Simple task runner integration for building and running your code
* Automatic redirection of program output to `output.txt`

## Manual Compilation & Execution

To compile and run manually from the terminal:

```bash
g++ main.cpp -o main
./main > output.txt
```

## Task Runner (Build, Compile, and Run)

Use the following shortcut to trigger build and run tasks automatically:

* **Windows/Linux**: `Ctrl + Shift + B`
* **Mac**: `Cmd + Shift + B`

This will compile `main.cpp` and execute the output, redirecting the result to `output.txt`.

## Devcontainer Support

The included `.devcontainer` sets up everything you need:

* Installs `g++` for C++ compilation
* Configures the VS Code workspace for smooth development

---