# README

## Brief introduction

"tiny_c" is a student project used to learn and practice c++ programming and software engineering skills.

Now, this project is at the beginning stage, so it has no output yet.

---

The recent goal of this project is to develop a C interpreter. This interperter is planned to support the 
following C language features:

1. Basic features: include basic variable definition, expression evaluation, loops, if and switch.

2. break and continue statement.

3. Macro: simple macro support.

4. struct definiton.

5. function definition.

6. support for pointer and array.

7. (maybe not) typedef statement.

---

If the developer can complete the development of these functions, the next goal is developer a debugger based 
on the interpreter, which may act like a tiny gdb.

The longer term plan for this project, is a compiler based on LLvM, which the developer at present knows 
nothing at all. However, The developer will try his best to collect enough time and energy to learn more and 
overcome the challenges. Good luck to me!


## Structure

The structure of this project in tree comes as follows:
.
├── README.md
├── build
├── compile_commands.json
├── doc
│   └── dev
├── include
├── src
│   ├── interpreter
│   ├── lexical_analyzer
│   ├── parser
│   └── preprocessor
└── xmake.lua

9 directories, 3 files

Updated in 2024-03-10 Sun 23:47:31

