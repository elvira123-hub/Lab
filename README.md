# Lab

## Import Modules
To simplify coding and scientific computing, the following Python libraries are commonly used:
- [NumPy](https://numpy.org/): Numerical computations and array operations.
- [SciPy](https://scipy.org/): Scientific computing, numerical algorithms, and optimization.
- [SciPy](https://matplotlib.org/): Data visualization, plotting graphs, and creating figures.

## Additional resources: 
#### [Python website](https://wiki.python.org/python/archive/UsefulModules.html):

- Python Useful Modules: A collection of additional Python libraries and modules.



# Hartree–Fock Method Using Python

## Project Overview

This project explores the numerical implementation of the Hartree–Fock (HF) method using Python to perform electronic structure calculations on simple molecular systems.

The code demonstrates the fundamental principles of quantum chemistry, including the construction of molecular orbitals, evaluation of electronic integrals, and iterative solution of the Hartree–Fock equations using the self-consistent field (SCF) procedure.

## Objectives

- Implement the Hartree–Fock method using Python.
- Explore the mathematical foundations of electronic structure calculations.
- Construct molecular orbitals using Gaussian-type basis functions.
- Investigate the electronic structure of simple molecular systems.
- Develop practical skills in scientific programming and numerical quantum chemistry.

## Computational Methods

### Hartree–Fock Theory

The Hartree–Fock method approximates the many-electron wavefunction using a single Slater determinant.

The electronic structure is determined by solving the Hartree–Fock equations iteratively until self-consistency is achieved.

### Basis Set

The implementation uses the minimal STO-3G basis set.

Each Slater-type orbital (STO) is approximated using a linear combination of three primitive Gaussian-type orbitals (GTOs).

### Self-Consistent Field (SCF) Procedure

The Hartree–Fock algorithm involves:

1. Constructing the overlap matrix.
2. Calculating the one-electron integrals.
3. Evaluating the electron–electron repulsion integrals.
4. Constructing the Fock matrix.
5. Solving the generalized eigenvalue problem.
6. Updating the electronic density matrix.
7. Repeating the procedure until convergence.

## Molecular Systems

The code includes parameters for the following systems:

- **H₂:** Hydrogen molecule.
- **HeH⁺:** Helium hydride cation.

The molecular geometry is represented by two atoms positioned along the x-axis, with the internuclear distance defined as an adjustable parameter.

## Python Libraries

The project uses the following Python libraries:

- [NumPy](https://numpy.org/): Numerical computations, matrix operations, and linear algebra.
- [SciPy](https://scipy.org/): Scientific computing and mathematical functions.
- [Matplotlib](https://matplotlib.org/): Visualization of numerical results and molecular orbitals.
- [time](https://docs.python.org/3/library/time.html): Monitoring computational execution time.
- [copy](https://docs.python.org/3/library/copy.html): Copying Python objects and data structures.

## Code Structure

The implementation is organized into several sections:

1. Importing Python libraries.
2. Defining physical constants and computational parameters.
3. Constructing Gaussian basis functions.
4. Defining molecular geometry.
5. Setting SCF convergence parameters.
6. Implementing the Hartree–Fock equations.

## Computational Parameters

The implementation includes:

- STO-3G basis functions.
- Adjustable internuclear distance.
- Nuclear charges and atomic parameters.
- SCF convergence threshold.
- Atomic units for molecular calculations.

## Reproducibility

The code provides explicitly defined physical constants, molecular geometries, basis-set parameters, and convergence criteria to support reproducible calculations.

## References

Add relevant references to the Hartree–Fock method, Gaussian basis sets, and numerical electronic structure calculations.

## Author

Add your name and GitHub profile here.
