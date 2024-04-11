# Brainf*ck Interpreter

This is a [brainf*ck](https://esolangs.org/wiki/Brainfuck) interpretter written in C++ for CodeCraft 2024 conducted by pclub iitk.

It is fully consistent with the brainf*ck standard. One thing that I could not find any consistant info about was the "," operator, I have set it to take a single char value as input.

## Building
This is a simple c++ program and can easily be built via `g++` and the likes. The linux binary can be found in the [Releases Section](https://github.com/code-IM-perfect/brainf_ckCompiler/releases). Windows binary are also available but are untested (I'm sorry I don't have enough space to dualboot). Mac users will have to compile it themselves unfortunately

```
g++ main.cpp -o interpreter
```

## Usage
After running the executable, just feed in the brainfuck commands.\
Use `q` to exit the interpretter (you can always use the good ol' `ctrl+c` tho haha)
