Description:
The project reads an sic input file and passes throught the file. The program reads
each line and segments it into three variables, the label, operation, and operand. 
The program checks if the sic file contains any errors and illegal statements such
as blank lines, a label that is a sic opcode, and a memory value outside of sic memory.
If no errors are found, the program keeps track of the current memory in hexadecimal and increments it
depending on the operation and operand. This tracking is used to store along with any labels
into a symbol table. The project prints out the symbol table log as labels are being added, 
the final symbol table contents, and a summary of the memory used by the sic program, including
the starting address, ending address, and program size.

Extra Credit:
Attempted

Experience:
The beginnning of the project was difficult because of how many functions and variables
I had to work with. I was also unfamiliar with pass 1 method at the time so looking at the
code was confusing. However, after learning how to complete pass 1 the project because simple.
The symbol table and insert methods were very similar to project 1 and did not create any 
difficulties. Parsing the file, making the errors, and completing directives and opcodes c files
were also relatively easy. One area that challenged me was the addressing. At first, the address 
would print out in decimal format and the incremental values from the directive and opcode function
would also have the same problem. However, my initilializing the address in hex with the start directive
all proceeding operations would automatically convert to hexadecimal and would print out correctly.
Overall, having completed project 1 and knowing how to do pass 1, the project was not incredibly challenging.

Shortcomings:
No Shortcomings.

Improvements:
No Improvements.

