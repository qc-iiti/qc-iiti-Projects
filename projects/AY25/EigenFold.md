# EigenFold
Repo Link: [Click Me](https://github.com/arhamaneeq/qc-EigenFold.git)

A hybrid quantum–classical framework for simulating lattice-based protein folding using QUBO formulation and Variational Quantum Eigensolvers (VQE).

## Key Principles
- `Protein Folding`: Modeled as an optimization problem seeking the lowest-energy 3D configuration of amino acids.
- `QUBO Formulation`: Encodes lattice folding constraints (adjacency, self-avoidance, hydrophobic contacts) into a binary optimization model.
- `VQE`: A hybrid quantum–classical algorithm used to minimize the Pauli Hamiltonian derived from the QUBO.
- `Binary Encoding`: Reduces qubit scaling from $O(RS)$ to $O(R\log S)$, enabling tractable simulations for multi-residue systems.
- `Energy Decomposition`

## Features
- QUBO-to-Hamiltonian transformation
- Binary encoding for efficient qubit use
- Multi-lattice folding simulations (sc, bcc, fcc)
- Automated energy-entropy analysis and visualisation

## Technologies Used
- `Qiskit`
- `NumPy`, `Matplotlib` `Pandas`

## Papers Referenced
- G Barnes, *VQE for Protein Folding*, 2024
- Doga et al., *Quantum Structure Prediction*, 2023
- Robert et al., *Resource Efficient Quantum Folding*, 2021
- Miyazawa & Jernigan, *Effective Interresidue Contact Energies*, 1985

## Author
- `Arham Aneeq`, BTech MEMS, IIT Indore, Class of 2028
