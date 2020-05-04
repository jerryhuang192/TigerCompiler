COMPSCI553: Compiler Construction

Tiger to MIPS compiler written in SML.  

###  Steps

- LEXING
- PARSING
- SEMANTIC ANALYSIS
- INSTRUCTION SELECTION
- LIVENESS ANALYSIS
- REGISTER ALLOCATION
- ASSEMBLY/LINKAGE
- MIPS ASSEMBLY

###  TIGER LANGUAGE DOCUMENTATION

http://www.cs.columbia.edu/~sedwards/classes/2002/w4115/tiger.pdf

###  USAGE

From the SML REPL, enter the directory containing the compile. 

```sml
OS.FileSys.chDir(compilerPath/)
CM.make "sources.cm";
Main.compile "/path/test.tig";
```

Produces an MIPS assembly file in the same directory as the target file that can be compiled using a MIPS simulator.
