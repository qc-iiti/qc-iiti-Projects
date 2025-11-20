## Quantum Battleship Using the Elitzur–Vaidman Interaction-Free Measurement Protocol  
**Repo Link:** [Click Me](https://github.com/Hemal2510/IISC-HACATHON)


A quantum–mechanical framework for interaction-free ship detection in a Battleship-style environment using the **Elitzur–Vaidman (EV) protocol** and IBM Quantum systems. This project demonstrates counterfactual measurement — extracting information about hidden ships *without directly interacting* with them — by leveraging quantum interference collapse as a detection mechanism.

---

## Objective  
Identify all ships on the Battleship grid with the **minimum possible chance of hitting or interacting with them**, enabled by the EV interaction-free measurement strategy.

---

## Key Principles  

### Interaction-Free Measurement (IFM)  
Uses the Elitzur–Vaidman protocol to detect the presence of an object by observing interference loss, enabling ship detection without firing a classical shot.

### Mach–Zehnder Interferometry  
Implements a two-path interference setup where the presence of a ship collapses the interference pattern, providing a probabilistic but interaction-free detection signal.

### Counterfactual Radar Logic  
Maps quantum measurement outcomes to game-state updates:  
- **Preserved interference** → no ship  
- **Interference collapse** → ship present (interaction-free detection)  
- **Direct detection events** → rare classical hits due to protocol limitations  

### Quantum–Classical Integration  
Combines quantum circuit execution with a classical Battleship engine to compute deterministic radar outcomes from probabilistic quantum measurements.

---

## Features  
- Full EV-based probe circuit implemented using Qiskit  
- Interaction-free radar scans executed on IBM Q hardware/simulators  
- Automated interpretation of measurement outcomes  
- Grid-based detection logic adapted to the Battleship game framework  
- Noise analysis for real-device executions  
- Demonstration of quantum advantage in detecting objects with minimal interaction  

---

## System Workflow  
1. Generate Elitzur–Vaidman probe circuit.  
2. Execute on IBM Q (Aer or real backend).  
3. Read and classify measurement results.  
4. Update board state through a classical logic engine.  
5. Iterate to complete a full-board scan with reduced detection cost.  

---

## Technologies Used  
- **Qiskit**  
- **IBM Quantum**  
- **Python**  
- **NumPy, Matplotlib** (optional for analysis)

---

## Background References  
- A. Elitzur & L. Vaidman, *Foundations of Physics*, 1993  
- P. Kwiat et al., Enhanced Interaction-Free Measurements, 1995  
- IBM Quantum Documentation  
- Nielsen & Chuang, *Quantum Computation and Quantum Information*

---

## Contributors  
**Hemal**  

