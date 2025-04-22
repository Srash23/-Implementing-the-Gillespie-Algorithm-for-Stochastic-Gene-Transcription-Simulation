# Gene Regulatory Network Simulation

This repository presents simulations of gene expression dynamics using systems of ordinary differential equations (ODEs) and stochastic modeling. It demonstrates how transcriptional regulation, degradation, and feedback influence molecular dynamics in synthetic gene networks.

## Project Overview
This modeling pipeline simulates:
- mRNA and protein dynamics via ODEs
- Two-gene and three-gene feedback loops
- Hill function-based activation and repression
- Stochastic transcription via Gillespie algorithm

## Simulated Models

### Basic mRNA-Protein Dynamics
- Deterministic ODEs
- Simulates production and degradation

### Two-Gene Activation Network
- Gene 1 activates Gene 2
- Hill function implementation

### Two-Gene Repression Network
- Gene 1 represses Gene 2
- Inhibitory Hill function

### Three-Gene Feedback Circuit
- Gene 1 → activates Gene 2
- Gene 2 → activates Gene 3
- Gene 3 → represses Gene 1

### Gillespie Simulation
- Stochastic modeling of transcription events
- Captures noise in mRNA levels over time

## Requirements
```bash
pip install numpy matplotlib scipy
```

## Output Visualizations
- Time-series plots of mRNA/protein levels
<img width="546" alt="Screenshot 2025-04-21 at 11 21 10 PM" src="https://github.com/user-attachments/assets/ed648b64-93cb-4727-b0d6-d6ef131e72ed" />

- Subplots for each gene in multi-gene systems
<img width="836" alt="Screenshot 2025-04-21 at 11 20 37 PM" src="https://github.com/user-attachments/assets/60666a5b-0dba-4c3b-8ef3-af4ca03fa051" />

- Gillespie trajectory for stochastic transcription
<img width="556" alt="Screenshot 2025-04-21 at 11 20 16 PM" src="https://github.com/user-attachments/assets/e8509c45-f94e-43b9-9748-3425194c3c79" />

## Example Execution
Run any simulation script directly in Python.
```bash
python ode_simulation.py
python gillespie_simulation.py
```
## License
MIT License
