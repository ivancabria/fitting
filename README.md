The name of the code is 'fitting'

This code fits a set of points of the type (z,V), (x,y,V),
(x,y,z,V), (x,y,z,s,V), (x,y,z,s,t,V) or (x,y,z,s,t,u,V)
by means of the Linear Least Squares Method, to a fitting
function that consists on a linear combination of a set
of basis functions. V=V(z), V(x,y), V(x,y,z), V(x,y,z,s),
V(x,y,z,s,t) or V(x,y,z,s,t,u)

V is the function
x,y,z,s,t,u are the variables

The code is written in fortran and only for Unix/Linux environments.

It has been compiled and tested on different hosts based on Unix/Linux

The file fitting-source.tar.gz contains the source code and the makefile file

To compile the code:
a) tar zxvf fitting-source.tar.gz    The files will be in the directory fitting/source
b) cd fitting/source
c) Enter 'make' or 'make -s'

The file fitting-inputandoutputfiles.tar.gz contains some examples of input files and their 
corresponding output files

To run the code:
fitting < inputfile > outputfile &
