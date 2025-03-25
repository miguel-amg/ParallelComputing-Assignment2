# Parallel Computing 

**Authors:** Miguel Jacinto Dias Carvalho [(Github)](https://github.com/MiguelJacintoML), Miguel Guimarães [(Github)](https://github.com/miguel-amg), Pedro Carneiro [(Github)](https://github.com/PedroCarneiro03).

**University of Minho** - Masters's degree in Software Engineering

**Year 2025**

***

**Assignment #2**
The objective of this assignment is to improve the execution time by exploring shared-memory parallelism with OpenMP
directives. The starting point for this second phase is the improved version of phase 1 with two changes:

1. Data size should increase from SIZE=42 to SIZE=84 (8 fold-increase in data size).
2. A new solver, more efficient and suitable for parallel execution, must be used. This solver is a red-back implementation with convergence check (see attached file for the new solver code).

In this assignment, the following steps must be followed:
- **(i)** identify the application hot-spots (code blocks with high computation time)
- **(ii)** analyse and present the alternatives to explore parallelism within the hot-spots identified in **(i)**
- **(iii)** select an approach to explore parallelism, justified by a scalability analysis
- **(iv)** implement and optimise the approach on the SeARCH cluster (compute node(s) on cpar queue)
- **(v)** measure and discuss the performance of the proposed solution
