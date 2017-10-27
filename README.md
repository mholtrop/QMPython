# QMPython
Quantum Mechanics and Schrodinger Equation Solvers in Python.

The starting point for these calculations is the notebook "Solving_the_Schrodinger_Equation_Numerically.ipynb".
In this notebook you will find an explanation on how to setup the Hamiltonian
for an infinite square well. It is very easy to change this to any shape potential,
bounded on some domain [xlow,xhigh].

An example usage of this way of solving the Schrodinger equation in this way can
be found in Harmonic Oscillator.ipynb, which shows how a harmonic state of
the H.O. evolves over time. This problem is exactly solvable using the algebra of
ladder operators, and agrees with the numerical solution here. You can play some
games with this notebook, for example by adding a spike in the center of the well.

A different solution, solving the Time Dependent Schrodinger Equation directly
is found in TimePropagation_of_WF.ipynb. This still uses the Hamiltonian, but
now solves the time dependence directly, stepping in time. This makes for good
solutions to scattering problems.

## Content

- Solving_the_Schrodinger_Equation_Numerically.ipynb
- Harmonic Oscillator.ipynb
- TimePropagation_of_WF.ipynb
