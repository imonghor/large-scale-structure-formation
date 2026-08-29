# Large-Scale Structure

### Computational exploration of cosmic expansion, structure formation, and the cosmic web

This project investigates how small primordial density fluctuations evolve under cosmic expansion and gravitational instability to produce the large-scale structure of the Universe.

The long-term goal is to develop a simple computational framework for studying the connection between **cosmic expansion history** and the **morphology/statistics of the cosmic web**.

---

## Research Question

> **Can the morphology of the cosmic web retain a measurable signature of the expansion history of the Universe?**

We approach this question by progressively developing a computational model of structure formation, beginning with the background expansion of the Universe and eventually evolving matter distributions into a cosmic web.

---

## Project Roadmap

```text
Friedmann Equation
       │
       ▼
Cosmic Expansion
       │
       ▼
Density Perturbations
       │
       ▼
Linear Growth
       │
       ▼
Zel'dovich Approximation
       │
       ▼
Particle Evolution
       │
       ▼
Density Field
       │
       ▼
Cosmic Web
       │
       ▼
LSS Statistics & Morphology
```

### Phase I — Cosmic Expansion

* Friedmann equation
* Scale factor \(a(t)\)
* Hubble parameter \(H(a)\)
* Matter and dark-energy dominated eras
* Redshift and lookback time

### Phase II — Structure Formation

* Density contrast \(\delta\)
* Linear perturbation theory
* Growth factor \(D(a)\)
* Gravitational instability
* Initial density fields

### Phase III — From Perturbations to Structure

* Zel'dovich approximation
* Particle displacement
* Periodic boundary conditions
* Particle-mesh gravity
* Numerical evolution

### Phase IV — Cosmic Web

Identify and study:

* Clusters
* Filaments
* Sheets
* Voids

### Phase V — Quantitative Analysis

Measure:

* Density probability distribution
* Two-point correlation function
* Matter power spectrum
* Void statistics
* Filament statistics
* Morphological descriptors

---

## Current Status

🚧 **Early development**

The project currently focuses on establishing the cosmological background and building the computational framework required for structure-formation simulations.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/large-scale-structure.git
cd large-scale-structure
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

### Windows

```bash
.venv\Scripts\activate
```

### Linux/macOS

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Dependencies

The project currently uses:

* Python
* NumPy
* SciPy
* Matplotlib

Additional scientific packages will be introduced as the project develops.

---

## Repository Structure

```text
large-scale-structure/
│
├── docs/          # Physics notes and theoretical background
├── src/lss/       # Reusable scientific code
├── notebooks/     # Experiments and analysis
├── simulations/   # Simulation outputs and documentation
├── figures/       # Generated scientific figures
└── data/          # Input data
```

---

## Scientific Philosophy

The project is being developed from first principles wherever practical.

Rather than treating a simulation as a black box, we aim to understand the physical and mathematical structure behind each component:

$$
\text{Expansion}
\rightarrow
\text{Perturbations}
\rightarrow
\text{Growth}
\rightarrow
\text{Gravity}
\rightarrow
\text{Structure}.
$$

The goal is therefore not simply to produce visually impressive simulations, but to connect the numerical results to physical predictions.

---

## Future Directions

Possible extensions include:

* Alternative cosmological expansion histories
* Modified gravity
* Different initial power spectra
* Higher-resolution simulations
* Cosmic-web classification
* Machine-learning-based morphology analysis
* Comparison with observational large-scale-structure data

---

## Project Status

This repository is an ongoing research and learning project.

More details, theoretical notes, computational methods, and results will be added as the project develops.
