---
title: "Solvers"
permalink: /solvers/
---

The repository contains the solver code used for the QUBO benchmarks.


### Classical Solvers

- **Classical reference solver:** A self-contained Python solver based on
  low-rank Burer-Monteiro relaxation, random-hyperplane rounding, variable
  fixing, and greedy bit-flip polishing. An optional C++ kernel accelerates the
  sparse objective and gradient calculations.
- **Gurobi:** A legacy benchmark interface for the commercial optimizer.
- **Geno:** A legacy benchmark interface for continuous relaxation.

### Quantum Solvers

- **D-Wave Advantage:** An interface using D-Wave Ocean and recorded runs from
  the JUPSI system at the Jülich Supercomputing Centre.

Source code and instructions are available in the
[QUBO benchmark repository](https://github.com/ml-uhh/qubo-benchmark#classical-reference-solver).

