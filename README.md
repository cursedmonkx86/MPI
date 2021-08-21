# MPI
Usage of MPI in HPC during C-DAC certification training

mpi-2.c is MPI program in C for calculating biggest prime number and number of prime numbers between 0 to largest number

************************************************************************************************************************

Make sure MPI is installed in the system along with supporting libraries and compilers

**************************************************************************************

For compiling mpi-2.c program:

mpicc mpi-2.c -o test -lm

test is executeable file of mpi-2.c

To execute the program:

mpiexec -n {number of processes} ./test

number of processes either 4 or 8. Ignore {}
