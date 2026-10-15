# Quantum Simulation of the XXZ Spin Chain

**Collaborative University of Edinburgh Quantum Computing project**

This repository contains a cleaned public version of the original group notebook for the project **“Quantum Simulation of the XXZ Spin Chain using Trotterized Quantum Circuits.”**

The project studies real-time dynamics in a one-dimensional XXZ spin chain using Trotterized quantum circuits, classical exact time evolution, noisy-circuit simulation, Fourier analysis and IBM Quantum hardware.

## Authors

- Bhoopesh Dosieah
- Saqib Umair
- Anay Chadha
- Shailesh Devarasu
- Akshat Dalmia
- Hamish Cranston

This repository is **not presented as solely my work**.

## My contribution — Saqib Umair

The contribution record in the submitted group project lists my work as:

- **Initial-state preparation**
- **Local observables**
- **Fourier analysis**
- **IBM hardware result analysis**

I therefore claim only these parts as my direct contribution.

## Other recorded contributions

| Contributor | Contribution |
|---|---|
| **Bhoopesh Dosieah** | XXZ Hamiltonian implementation; introduction; analysis methodology; site comparison |
| **Saqib Umair** | Initial states; observables; Fourier analysis; IBM result analysis |
| **Anay Chadha** | Trotter circuit; accuracy evaluation |
| **Shailesh Devarasu** | Classical exact benchmarks; time-evolution algorithm |
| **Akshat Dalmia** | Quantum-circuit evolution; noisy-circuit evolution; simulations; code integration |
| **Hamish Cranston** | Fourier plots; IBM hardware execution |

The distinction between related tasks is intentional. For example, my contribution was **IBM result analysis**, while Hamish Cranston carried out the **IBM hardware execution**.

See [`CONTRIBUTIONS.md`](CONTRIBUTIONS.md) and [`ACKNOWLEDGEMENTS.md`](ACKNOWLEDGEMENTS.md) for the attribution statement.

## Notebook

The full analysis workflow is available here:

[`notebooks/XXZ_spin_chain_quantum_simulation.ipynb`](notebooks/XXZ_spin_chain_quantum_simulation.ipynb)

The notebook includes:

- XXZ Hamiltonian construction;
- physically motivated initial states;
- local Pauli observables;
- first- and second-order Suzuki–Trotter evolution;
- classical exact time evolution;
- site-resolved comparison;
- Trotter error studies;
- two-dimensional Fourier analysis;
- noisy-circuit simulation;
- IBM Quantum hardware analysis.

## Public-version changes

The public notebook preserves the scientific content, code, outputs and contribution record, but two security/privacy changes were made before upload:

- student identification numbers were removed;
- a hard-coded IBM Quantum API credential was removed and replaced by an environment-variable workflow.

No source code was reconstructed from the PDF report. The uploaded notebook is based on the original group notebook provided for this project.

## Tools

Python · Qiskit · NumPy · SciPy · Matplotlib · IBM Quantum

## Scope

This is a collaborative academic project and should be read as such. The repository is intended to demonstrate my own contribution within the wider group work, not to claim sole authorship of the full project.
