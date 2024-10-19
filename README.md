# Quantum Fourier Transform (QFT) in Qiskit

## Overview
This repository demonstrates the implementation of the **Quantum Fourier Transform (QFT)** using the Qiskit library. The QFT is a key quantum algorithm that transforms the state of qubits from the computational basis to the Fourier basis, facilitating various quantum algorithms, including **Shor's algorithm**.

## Objectives
- Understand the concept of the **Quantum Fourier Transform**.
- Implement a **5-qubit QFT circuit** using Qiskit.

## Implementation
The project includes the creation of a quantum circuit with **5 qubits**. The following key components are implemented:

-**Hadamard Gates**
Used to create superposition on the qubits.

-**Controlled Phase Gates**
Apply rotations that adjust the phase of qubits based on their states.

-**Measurement**
Measure the final state of the qubits and output the results.

## Circuit Visualization
The quantum circuit is visualized to illustrate the gates and operations applied during the QFT process, showcasing the structure of the QFT implementation.

## Inverse Quantum Fourier Transform
The inverse QFT is also discussed, which allows retrieval of original qubit values by reversing the operations performed during the QFT.

## Requirements
- **Qiskit library**
- **Matplotlib** for circuit visualization

## Output
The implementation produces the measurement results of the QFT applied to the initialized qubit states, demonstrating the transformation of qubit values into the Fourier basis.

## Conclusion
This project provides a hands-on understanding of the **Quantum Fourier Transform**, its implementation, and its significance in quantum computing.
