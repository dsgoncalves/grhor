Globalized RrhoR
------------------------------
Given a complete POVM set "E" and a vector of observed frequencies "r", 
the routine 'grrhor' compute the Maximum Likelihood estimate 
for the density matrix 'rho'.

Usage:
[rho,iter,nfun,flag] = grrhor(n,r,E,tol,opt,alpha0,rho00,maxit)

This routine runs under MATLAB® (http://www.mathworks.com/) or Octave® (https://www.gnu.org/software/octave/) environments. 

For more details, type 'help grrhor' into the respective enviroment's command line window and/or take a look at the examples in this folder.


Reference: D.S. Gon\c{c}alves, M.A. Gomes Ruggiero, C. Lavor.
Global convergence of diluted iterations in Maximum Likelihood 
Quantum Tomography. Quantum Information and Computation, 14:966--980,
2014

Copyright (C) 2014 D.S. Gon\c{c}alves, M.A. Gomes Ruggiero, C. Lavor.
