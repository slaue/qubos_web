---
permalink: /instances/
title: "Instances"
---


### Categories of QUBO Instances

The benchmark contains 1,912 evaluated QUBO instances in four families:

- **compsup:** 480 graph-structured instances supplied for the JUPSI benchmark.
- **random:** 23 randomly generated QUBOs.
- **s28-qac:** 1,386 Sidon-28 spin-glass instances at eleven size levels.
  This family follows the instances used in
  [*Scaling Advantage in Approximate Optimization with Quantum Annealing*](https://doi.org/10.1103/PhysRevLett.134.160601).
- **QPLIB:** 23 selected instances from
  [QPLIB](https://qplib.zib.de/) converted to the repository's QUBO format.

### Download QUBO Instances

The complete instance collection is available in the
[QUBO benchmark repository](https://github.com/ml-uhh/qubo-benchmark/tree/main/instances).

### Sources, Reproducibility, and Licensing

The S28/QAC family follows the generator and reference data published in the
associated [Harvard Dataverse dataset](https://doi.org/10.7910/DVN/PCLEHG).
For reproducibility, the benchmark repository includes the instances, solver
code, run instructions, and recorded results used in the comparisons. Its
[MIT License](https://github.com/ml-uhh/qubo-benchmark/blob/main/LICENSE) covers
the software; third-party datasets retain their original terms.

### Contributing to Our Collection

If you have QUBO instances that you would like to contribute, please contact us at [soeren.laue@uni-hamburg.de](mailto:soeren.laue@uni-hamburg.de).


