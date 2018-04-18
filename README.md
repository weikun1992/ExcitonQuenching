# ExcitonQuenching
Calculation of ionization quenching correction factors in plastic scintillators


## Installation
Linux (Tested on Ubuntu 16.04)

This version was tested with

* Python2.7
* Cython 0.27 or newer 
* GNU Make v. 4.1

Install e.g. with

* sudo apt-get install make
* sudo apt-get install cython

## Run an example

Compile the cython code used to solve the Blanc equation
1. cd ExcitonQuenching/cython
2. make

should create the share object evolveDensitiesCython.so

1. cd ../
2. python2.7 main.py

should run a test version



