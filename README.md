# MQE – Quantum Chemistry Project

Quantum computing simulations for molecular systems using **Variational Quantum Eigensolver (VQE)** methods.  
Developed as part of the *Quantum Engineering Project* masters course.

## Contents

- **molecular_vqe_baseline.ipynb**  
  Baseline VQE workflow for computing the ground-state energy of simple molecules (e.g., H₂, LiH) using parameterized quantum circuits.

- **h2_vqe_noise_analysis.ipynb**  
  Noise-aware VQE simulations for H₂, exploring the effect of realistic hardware noise models (depolarizing, thermal relaxation, readout errors) on convergence and accuracy.

## Objectives
1. Implement VQE for molecular Hamiltonians obtained from quantum chemistry encodings (Jordan–Wigner, Parity).  
2. Compare performance of ideal vs. noisy simulators.  
3. Explore ansatz depth, optimizer choice, and noise mitigation techniques.  

## Requirements
- Python ≥3.9  
- [Qiskit](https://qiskit.org/) ≥0.44  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [SciPy](https://scipy.org/)

## Authors
Mina Hova (@pmyna)
Ema Dzhuninska (@emadzhuninska)
