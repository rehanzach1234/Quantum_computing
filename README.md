# Quantum Teleportation — Week 6

This repository contains the Quantum Teleportation notebook used for Week 6 exercises.

## Files
- `Quantum_teleportation_week6.ipynb` — Jupyter notebook with code, diagrams and results.  
  *(Local working file path used during development: `/mnt/data/Quantum_teleportation_week6.ipynb`.)*

## Description
The notebook demonstrates a teleportation circuit, runs it on an IBM Quantum backend via Qiskit Runtime (Sampler), and shows the resulting bitstring counts and a histogram.

## How to run locally
1. Create / activate a Python environment (conda recommended):
```bash
conda create -n qiskit_runtime python=3.10
conda activate qiskit_runtime
pip install qiskit qiskit-ibm-runtime matplotlib
# or: pip install -r requirements.txt
