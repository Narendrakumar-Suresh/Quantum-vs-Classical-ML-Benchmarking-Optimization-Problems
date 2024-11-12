# Quantum vs Classical ML: Benchmarking N-Queens and Optimization Problems

This repository presents a research project comparing Classical Machine Learning (ML) and Quantum Machine Learning (QML) in solving optimization problems, including the N-Queens problem. The research focuses on benchmarking the performance and efficiency of both approaches using execution time, accuracy, and scalability metrics.

## Research Overview

Key objectives of the research:
- **Comparison of Classical and Quantum Algorithms**: We compare classical algorithms and quantum algorithms like QAOA for solving combinatorial problems such as N-Queens.
- **Performance Metrics**: Both approaches are evaluated on execution time, accuracy, and scalability, particularly for large datasets.
- **Optimization Problems**: The N-Queens problem is used as a case study, alongside other combinatorial problems.

## Benchmark Results

| N  | Classical Solution | Classical Execution Time (s) | Quantum Solution | Quantum Execution Time (s) |
|----|---------------------|-----------------------------|------------------|----------------------------|
| 4  | 1                   | 0.0001                      | QAOA Solution    | 2.0302                     |
| 8  | 1                   | 0.0009                      | QAOA Solution    | 1.3077                     |
| 12 | 1                   | 0.0027                      | QAOA Solution    | 3.2144                     |
| 16 | 1                   | 0.1221                      | QAOA Solution    | 21.5952                    |
| 20 | 1                   | 3.1303                      | QAOA Solution    | N/A (warning during execution) |

## Visualization of Solutions
***N-Queens Problem:***
![Comparison of Quantum and Classical Model Speeds](https://drive.google.com/uc?export=view&id=1zqCGIj4GsrlCd-cgPinDpzainy0X0jTC)

## Key Research Topics

- **Classical Algorithms**: Optimization and implementation of classical algorithms for N-Queens.
- **Quantum Algorithms**: Quantum Approximate Optimization Algorithm (QAOA) applied to N-Queens.
- **Comparative Analysis**: Comparing the performance and scalability of classical vs quantum solutions.
- **Scalability**: Testing both approaches on larger problem sizes.

## Requirements

- Python 3.x
- Qiskit or PennyLane (for quantum solutions)
- NumPy, Matplotlib, and other necessary libraries for classical solutions

## Collaborators

- [Av2901](https://github.com/Av2901)
- [GeraltofRivia001](https://github.com/GeraltofRivia001)
