# Tiny-C Compiler in Python

A simple compiler for a subset of the C programming language, implemented in Python for learning the fundamentals of compiler design.

## Features

- Lexical analysis and syntax parsing
- Abstract Syntax Tree (AST) generation
- Bytecode generation
- Stack-based virtual machine
- Variables (`a` to `z`)
- Arithmetic operations: `+`, `-`
- Comparisons: `<`
- Conditional statements: `if`, `else`
- Loops: `while`, `do-while`
- Basic syntax error detection

## Requirements

- Python 3.10 or later

## How to Run

```bash
python tiny_c_compiler.py
```

Enter a Tiny-C program in the terminal and press `Ctrl+Z`, then `Enter` on Windows to finish input.

## Example

```c
{
    a = 10;
    b = 20;
    c = a + b;
}
```

Output:

```text
a = 10
b = 20
c = 30
```

## Limitations

- Supports only a small subset of C.
- Only predefined integer variables are available.
- No functions, arrays, pointers, or native machine-code generation.
- Error reporting is basic.

## Purpose

This project demonstrates the basic stages of compiler design: lexical analysis, parsing, code generation, and execution using a virtual machine.

