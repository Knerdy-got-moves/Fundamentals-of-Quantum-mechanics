# Fundamentals of Quantum Mechanics

A comprehensive reading project exploring the foundational concepts of quantum mechanics, primarily based on Cohen-Tannoudji's "Quantum Mechanics" textbook.

## Author

**Rishi Paresh Joshi**
School of Physical Sciences, NISER
Supervised by Dr. Kush Saha

## Overview

This project provides a qualitative and intuitive exploration of fundamental quantum mechanical principles, demonstrating how quantum descriptions of physical systems differ radically from classical mechanics. The discussion focuses on single-particle systems, examining how quantum mechanics uses wave functions and probabilistic predictions rather than classical trajectories.

## Key Topics Covered

### 1. Wave-Particle Duality
- **Light Quanta and Planck-Einstein Relation**: Exploration of photons and the relationship between particle parameters (E, p) and wave parameters (ω, k)
- **Young's Double Slit Experiment**: Analysis of single-photon interference patterns and quantum unification of light
- **Principle of Spectral Decomposition**: Understanding measurement outcomes and eigenstates in quantum systems

### 2. Wave Functions and Schrödinger Equation
- **Classical to Quantum Transition**: De Broglie relations and the wave nature of matter
- **Bohr's Model**: Derivation of quantized energy levels and angular momentum
- **Schrödinger Equation**: Time evolution of quantum states and probability interpretation
- **Wave Packets**: Superposition of plane waves and Fourier analysis

### 3. Heisenberg Uncertainty Relations
- **Fourier Transform Uncertainty Principle**: Mathematical relationship between position and momentum spreads
- **Position-Momentum Uncertainty**: Physical implications of ΔxΔp ≥ ℏ/2
- **Time Evolution of Free Wave Packets**: Dynamics of quantum particle propagation

## Document Structure

```
Fundamentals-of-Quantum-mechanics/
├── Reading_project_on_Fundamentals_of_Quantum_Mechanics/
│   ├── Main.tex                        # Main LaTeX document
│   ├── Double Slit experiment.png      # Young's double slit experimental results
│   ├── Re(Psi) vs k.png               # Wave packet Fourier components
│   ├── Spectral decomposition.png      # Polarization and spectral decomposition
│   └── logo1.jpg                       # Institutional logo
├── .gitignore
└── README.md
```

## Compilation Instructions

### Prerequisites
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- REVTeX 4.2 package
- AMS-LaTeX 2.0
- BibTeX

### Building the Document

```bash
cd Reading_project_on_Fundamentals_of_Quantum_Mechanics
latex Main.tex
bibtex Main
latex Main.tex
latex Main.tex
```

Alternatively, using pdflatex:

```bash
pdflatex Main.tex
bibtex Main
pdflatex Main.tex
pdflatex Main.tex
```

## Mathematical Foundations

The document covers essential quantum mechanical relations:

- **Planck-Einstein Relation**: E = ℏω = hν
- **De Broglie Wavelength**: λ = h/|p|
- **Schrödinger Equation**: iℏ∂ψ/∂t = -ℏ²/2m Δψ + Vψ
- **Uncertainty Principle**: ΔxΔp ≥ ℏ/2

## Key Concepts Explained

### Quantum vs Classical Description

**Classical Mechanics:**
- State defined by position r(t) and velocity v(t) (6 parameters)
- Deterministic predictions via Newton's laws
- Well-defined trajectories

**Quantum Mechanics:**
- State characterized by wave function ψ(r,t) (infinite parameters)
- Probabilistic predictions: |ψ(r,t)|² gives probability density
- No definite trajectories; only probability amplitudes
- Measurement fundamentally disturbs the system

### Wave-Particle Duality

The document demonstrates that:
1. Photons don't have fixed trajectories
2. Initial conditions don't predict exact measurement outcomes
3. Only probabilities can be calculated from probability amplitudes
4. Particle and wave aspects are inseparable

## Experimental Evidence

The project discusses key experiments that established quantum mechanics:

- **Black Body Radiation**: Energy quantization (E = nℏω)
- **Compton Effect**: Confirmation of photon particle nature
- **Young's Double Slit**: Single-photon interference patterns
- **Davisson-Germer Experiment**: Electron diffraction confirming matter waves
- **Franck-Hertz Experiment**: Discrete atomic energy levels

## References

1. Cohen-Tannoudji, Claude, Bernard Diu, and Franck Laloë. *Quantum Mechanics*
2. [Bohr Model](https://en.wikipedia.org/wiki/Bohr_model) - Wikipedia

## Glossary

- **E**: Photon energy
- **p**: Momentum of the particle
- **k**: Wave vector
- **ω**: Angular velocity
- **ν**: Frequency
- **ℏ**: Reduced Planck constant (h/2π)
- **ψ**: Wave function

## License

This is an academic reading project. Please refer to the REVTeX 4.2 license for document class usage restrictions.

## Acknowledgments

Special thanks to Dr. Kush Saha for supervision and guidance, and to the School of Physical Sciences at NISER for academic support.

---

**Note**: This project demonstrates that quantum mechanics, while counter-intuitive from a macroscopic perspective, provides a coherent and experimentally verified framework for understanding matter and radiation at atomic and subatomic scales.
