# Quantum Algorithms — Qiskit

Implementations of fundamental quantum algorithms built from scratch using Qiskit,
as part of M.Tech in Quantum Computing at Defence Institute of Advanced Technology (DIAT), Pune.

## Algorithms

| Notebook | Description |
|---|---|
| `Grovers_Search_GeneralCase.ipynb` | Grover's search for n-qubits with dynamic oracle |
| `Quantum_Fourier_Transform.ipynb` | QFT and Inverse QFT from 1-qubit to n-qubit general case |
| `Quantum_Phase_Estimation.ipynb` | QPE for estimating eigenphases of unitary operators |
| `DeutschJozsa_nQubit.ipynb` | DJ algorithm for n-qubits with user-defined oracle |
| `Entanglement_Concurrence.ipynb` | Concurrence and linear entropy as entanglement measures |
| `Quantum_Teleportation.ipynb` | Teleportation protocol with classical feed-forward |
| `Superdense_Coding.ipynb` | Encoding 2 classical bits into 1 qubit using entanglement |

## Setup

```bash
pip install qiskit qiskit-aer matplotlib numpy
```

## Tools
- [Qiskit](https://qiskit.org/)
- Python 3.12
- AerSimulator for statevector and shot-based simulation
