## Overview 
This project implements a numerical solver for the 
one dimensional time-independent Schrodinger equation
for a simple potential models. The goal is to compute 
energy energy eigenvalues corrresponding wave functions 
using stable numerical methods. 


## Approach 
- the schrodinger equation is solved using "Numerov method"
  for second-order differential equation
- energy eigenvalues are determined using a root-finding
  algoritm (secant method)
- wave functions and probability densities are computed
  and visualized

the equation solved is :


$$-\frac{\hbar^2}{2m}\frac{d^2 \psi(x)}{dx^2} + V(x)\psi(x) = E\psi(x)$$




## Tools 
- python
- Numpy
- Matplotlib

## key results 
- computed bound-state energy levels for selected
  potential profiles
- verified numerical solutions against known analytical
  results
- visualized wave functions and probability densities

## Notes
This project focuses on numerical accuracy, convergence, and 
stability rather than symbolic or analytical solutions
