---
title: "Results"
permalink: /results/
---

### Benchmark Results

The table compares the best recorded objective values. A solver is better when
it returns the lower value. Of the 1,856 instances with results from both
approaches, the classical reference solver was better for 1,280 (69.0%) and
equal for 576 (31.0%). D-Wave did not return a result for 56 additional
instances.

| Instance family | Instances | Classical better | Equal | D-Wave better | No D-Wave result |
| --- | ---: | ---: | ---: | ---: | ---: |
| `compsup` | 480 | 80 | 360 | 0 | 40 |
| `random` | 23 | 13 | 7 | 0 | 3 |
| `s28-qac` | 1,386 | 1,177 | 200 | 0 | 9 |
| `QPLIB` | 23 | 10 | 9 | 0 | 4 |
| **All** | **1,912** | **1,280** | **576** | **0** | **56** |

The per-instance results and evaluation files are available in the
[QUBO benchmark repository](https://github.com/ml-uhh/qubo-benchmark/tree/main/results).
