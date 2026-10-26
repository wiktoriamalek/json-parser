# JSON Parser

A small C++ project that checks JSON syntax with hand-written validation routines for objects, arrays, strings, numbers, booleans, and `null`.

## Requirements

- A C++ compiler with C++11 support
- A JSON input file named `projekt.json` in the working directory

## Build and run

From the repository root:

```bash
g++ -std=c++11 json-og.cpp -o json-parser
./json-parser
```

Use the interactive menu to view help or run the validation operation. The program looks for `projekt.json` in the current directory.
