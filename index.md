---
title: "QUBO Solver Benchmark"
layout: single
---

##  Quantum vs Classical Solvers: Benchmarking QUBO Performance

Quadratic Unconstrained Binary Optimization (QUBO) problems describe decisions
with binary variables. For a matrix **Q**, the problem is

> **minimize xᵀQx over x ∈ {0,1}ⁿ.**

A solver searches for the binary vector **x** with the lowest objective value.

This project compares recorded results from a **D-Wave Advantage quantum
annealer** with **classical solvers** on the same QUBO instances. The benchmark
contains 1,912 instances, solver implementations, and per-instance results.

### Project Highlights

- **Benchmark data:** Four evaluated instance families cover graph-structured,
  random, spin-glass, and QPLIB problems.
- **Solver code:** The repository contains a self-contained classical reference
  solver, legacy interfaces for Gurobi and Geno, and a D-Wave interface.
- **Recorded results:** Of 1,856 instances with results from both approaches,
  the classical reference solver returned a lower objective value for 1,280 and
  the same value for 576.

The benchmark instances, solvers, and results are available in the
[QUBO benchmark repository](https://github.com/ml-uhh/qubo-benchmark).

