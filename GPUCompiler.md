# GPU compiler

## reference

https://www.opengl.org/sdk/docs/tutorials/TyphoonLabs/Chapter_3.pdf

## note

Design instruction with long physical continuous registers may take llvm tbl-gen long to build registerInfo table. Such as  register class regNclass where N  from 1..16, ld $reg16class, $(offset)$reg16class and reg16class may begin without alignment, such as beginning offset from r1, r2, ...

