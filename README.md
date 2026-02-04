# Emerging Technologies 2026

This repository contains solutions to problems exploring the difference between classical and quantum algorithms, with a focus on the Deutsch-Jozsa algorithm.

## Author

Cian Dicker Hughes
G00413415

## About

This project demonstrates quantum computing concepts using Qiskit, comparing classical and quantum approaches to solving Boolean function problems. The main deliverable is a Jupyter notebook (`problems.ipynb`) that addresses five problems related to Deutsch's and Deutsch-Jozsa algorithms.

## Problems Covered

1. **Generating Random Boolean Functions** - Creating constant and balanced Boolean functions
2. **Classical Testing for Function Type** - Determining function type using classical computation
3. **Quantum Oracles** - Implementing quantum oracles for Boolean functions
4. **Deutsch's Algorithm with Qiskit** - Quantum circuit implementation for single-bit functions
5. **Scaling to the Deutsch-Jozsa Algorithm** - Generalizing to four-bit Boolean functions

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. Clone this repository:
```bash
git clone https://github.com/CianDickerHughes/EMERGING-TECHNOLOGIES-2026.git
cd EMERGING-TECHNOLOGIES-2026
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook problems.ipynb
```

## Repository Structure

```
.
├── problems.ipynb      # Main notebook with problem solutions
├── README.md          # This file
├── requirements.txt   # Python package dependencies
└── .gitignore        # Git ignore rules
```

## Technologies Used

- Python
- Jupyter Notebook
- Qiskit (Quantum computing framework)
- NumPy
- Matplotlib

## References

- [Deutsch-Jozsa Algorithm - IBM Quantum Learning](https://quantum.cloud.ibm.com/learning/en/modules/computer-science/deutsch-jozsa)
- [Qiskit Documentation](https://www.ibm.com/quantum/qiskit)
- [Quantum Computing Fundamentals](https://quantum.cloud.ibm.com/learning)
