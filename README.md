# Research Environment

Cosmology Research Environment for

**Seokcheon Lee**  
Department of Physics, Sungkyunkwan University

Apple Silicon (MacBook Pro M5 Pro)

---

## Overview

This repository contains my personal research environment for modern cosmology.

Current research topics include

- General Relativity
- Modern Cosmology
- Hubble Tension
- Dynamical Dark Energy
- Large Scale Structure
- Growth of Structure
- Geometric Cosmological Time (GCT)
- minimally Extended Varying Speed of Light (meVSL)

The repository also provides a reproducible computational environment using

- Python
- CLASS
- CAMB
- Cobaya
- LaTeX
- Git/GitHub

---

## Directory Structure

```text
Research/
│
├── Codes/
│   ├── CLASS/
│   ├── CAMB/
│   ├── Cobaya/
│   ├── MontePython/
│   ├── Scripts/
│   └── Utilities/
│
├── Data/
├── Figures/
├── Papers/
├── Projects/
│
├── requirements.txt
└── README.md
```

---

## Software

### Operating System

- macOS Tahoe

### Editor

- Visual Studio Code

### LaTeX

- MacTeX 2026
- LaTeX Workshop

### Version Control

- Git
- GitHub (SSH)

---

## Python Environment

Environment

```
cosmo
```

Python

```
Python 3.14
```

Main packages

- numpy
- scipy
- matplotlib
- pandas
- astropy
- emcee
- corner
- GetDist
- CAMB
- CLASS (Python interface)
- Cobaya

---

## Cosmology Codes

Installed

- CLASS v3.3.4
- CAMB v1.6.6
- Cobaya v3.6.2

Planned

- MontePython
- OpenMPI
- mpi4py

---

## Git Repository

SSH

```bash
git@github.com:skylee2/research.git
```

Clone

```bash
git clone git@github.com:skylee2/research.git
```

---

## Typical Workflow

1. Develop theoretical models.
2. Modify CLASS or CAMB if needed.
3. Run parameter estimation using Cobaya or MontePython.
4. Analyze MCMC chains with GetDist.
5. Produce publication-quality figures.
6. Write papers in LaTeX.
7. Track all changes using Git and GitHub.

---

## Notes

- External cosmology codes (CLASS, CAMB, MontePython) are excluded from Git tracking.
- Large observational datasets are stored separately.
- Only source codes and important scripts are version controlled.

---

Last updated: June 2026