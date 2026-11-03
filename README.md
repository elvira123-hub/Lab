# Lab
# Hartree–Fock and Post Hartree-Fock Methods Using Python

## Import Modules
To simplify coding and scientific computing, the following Python libraries are commonly used:
- [NumPy](https://numpy.org/): Numerical computations and array operations.
- [SciPy](https://scipy.org/): Scientific computing, numerical algorithms, and optimization.
- [SciPy](https://matplotlib.org/): Data visualization, plotting graphs, and creating figures.
- [time](https://docs.python.org/3/library/time.html): Monitoring computational execution time.
- [copy](https://docs.python.org/3/library/copy.html): Copying Python objects and data structures.

## Additional resources: 
#### [Python website](https://wiki.python.org/python/archive/UsefulModules.html):

- Python Useful Modules: A collection of additional Python libraries and modules.


## Project Overview

The Lab work explores the numerical implementation of the Hartree–Fock (HF) and Post Hartree-Fock methods using Python to perform electronic structure calculations on simple molecular systems. The code demonstrates the fundamental principles of quantum chemistry, including the construction of molecular orbitals, evaluation of electronic integrals, and iterative solution of the Hartree–Fock equations using the self-consistent field (SCF) procedure.

## Objectives
- Implement the Hartree–Fock method using Python.
- Explore the mathematical foundations of electronic structure calculations.
- Construct molecular orbitals using Gaussian-type basis functions.
- Investigate the electronic structure of simple molecular systems.
- Develop practical skills in scientific programming and numerical quantum chemistry.

## Computational Methods
- **Hartree–Fock (HF):** Mean-field approximation.
- **Configuration Interaction (CI):** Post-Hartree–Fock method.
- **Second-Order Møller–Plesset Perturbation Theory (MP2):** Introduces electron correlation corrections to the Hartree–Fock energy through second-order perturbation theory.
- **Third-Order Møller–Plesset Perturbation Theory (MP3):** Extends MP2 by including third-order perturbative corrections to the electronic energy.


### Hartree–Fock Theory
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
