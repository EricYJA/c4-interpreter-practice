# c4-interpreter-practice
This is the practice code and notes taken when reviewing the c4 code and compiler keys. 


### Structure and Thinking

This code is based on the following links. 
[original c4 code](https://github.com/rswier/c4)
[write-a-C-interpreter code](https://github.com/lotabout/write-a-C-interpreter)
This is a rather simple idea inspiring sample which differs from actual implementation like clang or java compiler greatly. However, the key is to highligt the essenial algorithms and methods used in compiler building. 

I will highlight the key points of building a compiler in this README, which should be used as a reference and guideline. 

This code would first implement a virtal machine to simulate the memory behavior and the interaction between the hardware and the assembly code. Then the code would build a compiler based on the virtual machine. 

Here is a simple list when learning compiler throughly. 

1. Understand the computer architecture
2. Get familiar with an assembly language
3. Start building compilers!
  1. Understanding lexical analysis (lexer)
    1. regular expression
    2. finite-state machine
  2. Understanding parsing (parser)
    1. recursive down
    2. BNF
    3. EBNF
    4. left recursive
  3. Statement and Expression
    1. Unary Operator and all kinds of operator

