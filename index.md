---
title: "QUBO Solver Benchmark"
layout: single
---

##  Quantum vs Classical Solvers: Benchmarking QUBO Performance


This project is dedicated to benchmarking and comparing **classical and quantum solvers** for Quadratic Unconstrained Binary Optimization (QUBO) problems.

### Project Highlights
- **Set of QUBOs**: We provide an extensive benchmark of various QUBOs.
- **Comparison of Solvers**: We compare a variety of solvers for their speed and accuracy.
- **Classical vs Quantum**: Performance benchmarks for classical and quantum machines.


---

### What is a QUBO?

A **Quadratic Unconstrained Binary Optimization (QUBO)** problem is a mathematical optimization problem where the objective is to minimize a quadratic function of binary variables. Mathematically, a QUBO problem is represented as:

\[
\text{minimize} \: f(x) = x^T Q x
\]

Where:
- **x** is a vector of binary variables (0 or 1).
- **Q** is a matrix of coefficients representing interactions between variables.

QUBO problems are highly versatile and can represent a wide range of real-world applications, including:
- **Portfolio Optimization:** Maximizing returns while minimizing risk.
- **Logistics and Scheduling:** Efficiently assigning tasks or resources.
- **Machine Learning:** Feature selection or clustering.
- **Graph Problems:** Solving Max-Cut, Partitioning, or Covering problems.

---

### Why Are QUBOs Important?

QUBO problems play a central role in many industries due to their ability to model complex, real-world optimization tasks. However, solving large QUBO problems is challenging because they are **NP-hard**, meaning the computational effort required grows exponentially as the problem size increases.

#### Computational Complexity:
QUBO belongs to the class of NP-hard problems, which means that as the number of binary variables grows, the solution time grows exponentially in the worst case. 

---

#### Why Quantum Machines?
Recent developments in **quantum computing** offer the potential to solve QUBOs more efficiently. Quantum computing approaches such as:

- **Quantum Annealing:** Machines like D-Wave use quantum annealing for solving QUBOs by finding the global minimum.
- **Gate-based Quantum Computing:** Platforms like IBM's Qiskit and Google's quantum computers use algorithms such as the Quantum Approximate Optimization Algorithm (QAOA) to find approximate solutions to QUBOs.

### What We're Testing:
In this project, we aim to compare **classical solvers** with **quantum solvers**. We explore whether quantum machines can outperform classical ones in solving various types of QUBO problems, focusing on:
- **Speed**: How quickly can each solver find a solution?
- **Accuracy**: How close is the solution to the true global minimum?

---