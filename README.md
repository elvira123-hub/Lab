# Lab

## Import Modules
To simplify coding and scientific computing, the following Python libraries are commonly used:
- [NumPy](https://numpy.org/): Numerical computations and array operations.
- [SciPy](https://scipy.org/): Scientific computing, numerical algorithms, and optimization.
- [SciPy](https://matplotlib.org/): Data visualization, plotting graphs, and creating figures.

## Additional resources: 
#### [Python website](https://wiki.python.org/python/archive/UsefulModules.html):

- Python Useful Modules: A collection of additional Python libraries and modules.



# Numerical Solution of the Schrödinger Equation Using Python

## Overview

This project implements numerical methods in Python to solve the time-independent Schrödinger equation (TISE) and investigate quantum nuclear effects, with particular emphasis on isotope-dependent energy levels and zero-point energies.

## Features

- Numerical solution of the one-dimensional TISE.
- Calculation of quantum bound-state energies.
- Determination of zero-point energies (ZPE).
- Investigation of isotope-dependent quantum effects.
- Visualization of potential energy curves and wavefunctions.

## Numerical Methods

The time-independent Schrödinger equation is given by:

$$
\left[-\frac{\hbar^2}{2\mu}\frac{d^2}{dx^2}+V(x)\right]\psi(x)
=E\psi(x)
$$

where:

- $\hbar$ is the reduced Planck constant.
- $\mu$ is the reduced mass.
- $V(x)$ is the potential energy function.
- $\psi(x)$ is the wavefunction.
- $E$ is the energy eigenvalue.

The finite-difference method is used to discretize the Hamiltonian and calculate its eigenvalues and eigenvectors.

## Requirements

The project uses the following Python libraries:

- [NumPy](https://numpy.org/): Numerical computations and array operations.
- [SciPy](https://scipy.org/): Scientific computing and numerical algorithms.
- [Matplotlib](https://matplotlib.org/): Data visualization and plotting.

## Installation

Install the required dependencies:

```bash
pip install numpy scipy matplotlib
```

## Usage

Run the main Python script:

```bash
python main.py
```

Replace `main.py` with the actual entry-point filename.

## Results

The numerical calculations can be used to investigate:

- Quantum energy levels and wavefunctions.
- Zero-point energy differences between isotopes.
- Effects of the potential energy function on quantum bound states.

Include example figures and numerical results here.

## Reproducibility

To ensure reproducibility, document the input parameters, physical constants, numerical grid, boundary conditions, and convergence criteria.

## References

Add relevant publications and references describing the numerical methods and physical systems investigated.

## License

Specify the license governing the use and distribution of this project.
