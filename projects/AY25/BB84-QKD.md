# BB84-QKD
Repo Link: [Click Me](https://github.com/metamyteee/IISC-hackathon)

A hybrid quantum–classical simulation of the **Bennett–Brassard 1984 (BB84)** Quantum Key Distribution protocol using **Qiskit**, demonstrating secure key exchange and eavesdropper detection via **Quantum Bit Error Rate (QBER)**.

## Key Principles
- `Quantum Key Distribution (QKD)`: Establishes a shared secret key using quantum mechanics, ensuring security against computational attacks.
- `BB84 Protocol`: Uses non-orthogonal bases and the no-cloning theorem—measurement disturbs the quantum state, revealing interception.
- `QBER (Quantum Bit Error Rate)`: Quantifies transmission errors; high QBER indicates eavesdropping.
- `Quantum & Classical Channels`: Quantum channel for transmission, classical channel for key sifting and verification.
- `Security Threshold`: A key is accepted only if QBER ≤ 10%, ensuring communication integrity.

## Features
- Dual-mode simulation: `Secure` (no eavesdropping) and `Insecure` (Eve intercept–resend attack)
- Automated QBER calculation and key sifting
- Batch circuit execution for simulation efficiency
- Side-by-side results comparison for secure vs insecure cases

## Technologies Used
- `Qiskit`
- `NumPy`, `Matplotlib`

## Papers Referenced
- C. H. Bennett & G. Brassard, *Quantum Cryptography: Public Key Distribution and Coin Tossing*, 1984  
- Nielsen & Chuang, *Quantum Computation and Quantum Information*, 2010  
- Lo & Chau, *Unconditional Security of Quantum Key Distribution*, 1999  

## Author
- `Aarush (metamyte)`, BTech Engineering Physics, IIT Indore
