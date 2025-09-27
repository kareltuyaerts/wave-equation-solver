# Wave Equation Solver

*Scientific Software Project*

## Project Overview

A comprehensive implementation of multiple numerical methods for solving the wave equation in time domain. This project explores different discretization schemes, stability analysis, and parallel computing approaches for solving hyperbolic partial differential equations.

## Mathematical Background

The project focuses on solving the 2D wave equation:
∂²u/∂t² = c²(∂²u/∂x² + ∂²u/∂y²)

With various initial and boundary conditions representing different physical wave propagation scenarios.

## Implementation
Multiple simple numerical methods were implemented such as forward Euler, Heun and backward Euler. These methods were further optimized using techniques such as double time stepping and vectorization.

### Performance Optimization
- Cache-efficient memory access patterns
- Vectorization and compiler optimizations
- Scalability analysis and benchmarking

### Core Technologies
- **C++** - Primary implementation language for performance
- **Linear Algebra** - Custom sparse matrix operations
- **Visualization** - Data output for post-processing and animation

## Relevant Skills

- **Numerical Analysis**: PDE discretization methods
- **C++ Programming**: Efficient scientific computing implementation
- **Mathematical Modeling**: Physical wave phenomena simulation
- **Performance Engineering**: Code optimization and scalability analysis

---
