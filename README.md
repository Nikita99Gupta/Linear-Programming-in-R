# Linear-Programming-in-R
Linear programming (LP) is one of the simplest ways to perform optimization. 

Here we will take an example of linear problem and solve it using the library lpSolve to get desired maximisation or minimisation objective function output.

To solve a linear problem we need to first find the following -
1. decision variables - controllable inputs
2. parameters - uncontrollable inputs - coefficients
3. objective function - maximization or minimization problem
4. constraints - what requirements must be met - connections among variables

The objective function is:
Max.Z=25x+20y

where x are the units of pipe A

y are the units of pipe B

Constraints:
20x+12y<=2000
5x+5y<=540
