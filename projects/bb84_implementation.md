# Quantum Key Distribution (BB84 Protocol)

**Repo Link:** [Click Me!](https://github.com/namanshetty25/Quantum-Key-Distribution)

Quantum Key Distribution (QKD) is a secure communication method that uses quantum mechanics to enable two parties (commonly called Alice and Bob) to produce a shared, random secret key. This key can then be used to encrypt and decrypt messages with guaranteed security against an eavesdropper (Eve).

This repository provides an implementation and simulation of QKD protocols (currently BB84) in Python, along with interactive GUI tools, Bloch sphere visualizations, and performance analysis plots.

---

## Key Principles

- **BB84 Protocol:**  
  A quantum cryptography protocol developed by Bennett and Brassard in 1984, enabling secure key distribution using quantum states.

- **Quantum Superposition:**  
  Utilizes qubits' ability to exist in multiple states simultaneously to encode cryptographic keys.

- **Quantum Measurement:**  
  Ensures security by collapsing quantum states upon measurement, detecting potential eavesdroppers.

- **No-Cloning Theorem:**  
  Prevents unauthorized copying of quantum states, ensuring the integrity of the key exchange.

---

## Features

- **BB84 Protocol Simulation** with configurable parameters (qubits, Eve probability, test fraction)
- **Interactive Tkinter GUI** with real-time logs and results
- **Bloch Sphere Visualization** for Alice and Bob’s qubit states
- **Eve Probability Sweep Mode** to analyze error rates against eavesdropping
- **Batch Mode** for statistical evaluation over multiple runs
- **Export Results as CSV** for further analysis
- **Integration with PennyLane** for quantum circuit-based measurements

---

## Technologies Used

- **Python**: For protocol logic, simulation, and data processing
- **Tkinter**: For building the interactive GUI
- **PennyLane**: Quantum circuit-based measurements and integration
- **NumPy**: Numerical computations and random bit generation
- **Matplotlib**: Plotting key distribution results and error rates

---

## Authored by

- [Naman Shetty](https://github.com/namanshetty25), BTech EE, IIT Indore, Class of 2028
- [Siddha Nema](https://github.com/Siddhanema), BTech EE, IIT Indore, Class of 2028
- [Vanshika Gupta](https://github.com/VanshikaGupta001), BTech CSE, IIT Indore, Class of 2028
