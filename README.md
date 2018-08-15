# Introduction

This is an example implementation of a phase field model for cell motility on the GPU using CUDA. Feel free to use it as a starting point for your own projects, but  *please* cite the paper it's based on (see below).

The code here is based on the model utilized in the following paper:

 ` Kulawiak DA, Camley BA, Rappel W-J (2016) Modeling Contact Inhibition of Locomotion of Colliding Cells Migrating on Micropatterned Substrates. PLoS Comput Biol 12(12): e1005239. https://doi.org/10.1371/journal.pcbi.1005239`
 
Note, that this is NOT a full reimplementation and certain features are not implemented.

# Usage
Compile the program using the compile script (check if the architecture matches your card)  
Check the included example parameter file example_param.ini, move it to a folder of your choice and rename it to param.ini  
Start to program with ./name "folder"


# Todo
-   More documentation
-   Chemical interactions
-   Startscript
-   Scripts to analyse output
-   proper makefile
-   Unittests
