# README:  Tcl

This is the patch of **Tcl 9.1a1** source distribution, including a shorthand for expr, either at Tcl_Parser level, either in array component

With these files, you should be able to write :

> set A [(1+1)]; # set a value of 2 for A.
> set B((1+1)) 3; # set 3 at index 2 of array B 
