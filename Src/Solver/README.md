Directory for Solver which will solve the quadratic equation

The main method in quadsolver.c will calculate the quadratic equation and print roots to the user.  The makefile will pull all needed code from other directories to this directory to be compiled with the quadsolver.c and header file

The tester t1.c will test certain parts of the equation solving process.
The tester t2.c will test the quadsolver program with a mock mysqrt() function.

Makefile commands:

make a.out: the program
make d.out: the program along with debug information
make clean: clean up the file
