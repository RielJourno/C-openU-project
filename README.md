# C-openU-project

This project is an assignment in a C programming course at the open unvieristy (20465). The purpose of this project is to build an assembler for 15-instruction asssembly language, for an imaginary 24-bit CPU and 21 bits of memory size. This project was done by @RielJourno and @BenChoen. For any issues, questions and ideas turn to the Issues tab.

License: MIT License, Affect from September 1st, 2021

Directory structure (Modules)
assembler - main function definition, argv & argc processing, single file processing.
first_pass - contains functions for processing a single line in the first pass and a code line in the first pass.
second_pass - contains function for processing a single line in second pass and replacing symbol by it's address.
code - contains useful function for processing code.
instructions - contains useful function for processing instruction.
globals.h - contains type and constant definitions.
table - contains definition of table-like linked list data structure.
utils - contains general-purposed, project-wide functions.
writefiles - contains methods for writing output files: *.ob, *.ext and *.ent
