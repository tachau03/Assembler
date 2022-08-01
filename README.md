# Name of the Program: Assembler 
## Directions of using: 
Run assembler with a input file. Could turn on debuging to see more contents of the instructions.

Compile all the files: "make assembler"

To run the program: "./assembler <your MIPS file>"

If you want to turn on debugging enter: 
"./assembler <your MIPS file> 1" or "./assembler 1 <your MIPS file>"
For example: "./assembler Chou.mips 1"

## Program purpose: 
Read MIPS instructions and generate corresponding machine language instructions.

## Name
Chau Ta

## Date: 27/02/2022
## Modified: 2/1/2022
    Reason: Update top-of-file comments and internal comments. 
            Include signed version of printInt in PrintAsBinary
            
## Modified: 2/1/2022
    Reason: Accidentally git reset --hard
    
## Modified: 3/1/2022
    Reason: Include new version of printAsBinary, testPrintAsBinary
            assembler.h (include checking range for signed and 
            unsigned numbers). 
            Modify pass2 with signed and unsigned numbers
