CMSC 313 HW 7

Comparison of assembly files: 

The addmats.s file generated from the C++ code is much longer than the addmatsSimple.s and 
addmatsSubr.s generated from the C code, I would assume that this is because C++ makes use of 
more complex features such as classes whereas the C code does not. All 3 files have a section in 
the middle that is repeated which likely corresponds to the loop in their respective C++ and C 
files. The addmats.s file also has a lot more code before the main function, likely coming from 
the set up of the class and its functions which isn’t in the assembly files generated from the C 
code.

Comparison of basic.c and basic.s:

For all of the global variables in the assembly program, their size and type is explicitly defined. 
Looking at the general layout of the files, you can see that the variables in the assembly file are 
defined above the main function just as they are in the C file and that the main function has a 
loop within it that sets a = a just as it is in basic.c.

