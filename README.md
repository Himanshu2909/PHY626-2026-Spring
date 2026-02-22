# PHY626-2026-Spring: Quantum Mechanics II

**Instructor:** Prof. Tarun Kanti Ghosh 

## First Half

### Overview

* **Phase 1: The Algebraic Toolkit:** The course started by reviewing the Quantum Harmonic Oscillator. Instead of solving horrific differential equations, you learned to use algebraic "ladder operators" (creation  and annihilation  operators) to jump between energy levels. This mathematical trick makes calculating things much easier.
* **Phase 2: Static Tweaks (Time-Independent Perturbation Theory):** What happens if you take a perfectly solved system and add a small, static disruption? You use Perturbation Theory. You learned how to find the shifted energy levels (, ) and tweaked wavefunctions when the initial energy levels are unique (Non-degenerate) , and what to do when multiple states share the same energy (Degenerate).
* **Phase 3: The Real Hydrogen Atom:** You then applied these tweaks to the Hydrogen atom. The basic Bohr model isn't completely accurate. You calculated the **Stark Effect** (what happens when you put Hydrogen in an electric field). Then, you explored **Fine Structure**, which corrects the atom's energy by accounting for relativity, the electron's spin interacting with its orbit (Spin-Orbit coupling), and a quantum jitter called the Darwin term. Finally, you looked at the **Zeeman Effect** (putting the atom in a magnetic field). 
* **Phase 4: Dynamic Systems (Time-Dependent Perturbation Theory):** Real life involves things moving and changing. The final chunk of the course asks: what if the disruption changes over time?. You learned how to calculate the probability of a particle jumping from one state to another over time. This naturally led to studying magnetic resonance and **Rabi Oscillations**, which describe how a two-level system flips back and forth when driven by an oscillating field.

---

### Syllabus
| Detailed Topic from Notes | Pages of Notes | Section from Griffiths | Section from Sakurai |
|----------------------------|---------------|------------------------|----------------------|
| Harmonic Oscillator Formalism: Creation/Annihilation operators (a, a†), matrix elements of x and p, expectation values of Kinetic Energy | Pages 1 - 3 | 2.3.1 Algebraic Method | 2.3.1 Energy Eigenkets and Eigenvalues |
| Charged Particle in a Magnetic Field: Vector potential gauge choice, Cyclotron frequency, reduction to 1D Harmonic Oscillator, Landau Levels | Pages 4 - 6 | 4.4.2 Electron in a Magnetic Field | 2.7.3 Gauge Transformations in Electromagnetism |
| Addition of Angular Momentum: Spin and orbital angular momentum, Clebsch-Gordan coefficients, coupled vs. uncoupled basis | Pages 6 - 7 | 4.4.3 Addition of Angular Momenta | 3.8.1 / 3.8.2 Addition of Angular Momenta |
| Time-Independent Perturbation Theory (TIPT) - Non-Degenerate: First and second-order energy corrections, first-order wave function correction | Pages 8 - 12 | 7.1 Nondegenerate Perturbation Theory | 5.1.1 / 5.1.3 Formal Development of Perturbation Expansion |
| TIPT Applications (1D): Anharmonic oscillator (Morse potential approximation, cubic/quartic terms), constant electric field | Pages 12 - 19 | Chapter 7 Problems | 5.1.5 Elementary Examples |
| Static Two-Level Systems: Spin in a magnetic field, Pauli matrices perturbation, exact vs. perturbative solutions | Pages 19 - 21 | Chapter 7 Problems | 5.1.2 The Two-State Problem |
| TIPT - Degenerate: Isotropic 2D harmonic oscillator, breaking degeneracy via perturbations (e.g., xy term), block diagonalization | Pages 21 - 28 | 7.2 Degenerate Perturbation Theory | 5.2 Time-Independent Perturbation Theory: The Degenerate Case |
| Avoided Level Crossings: Quasi-degenerate systems, secular equation, perturbation wiping out initial states | Pages 28 - 29 | 11.1 Two-Level Systems | 5.1.2 The Two-State Problem |
| Stark Effect in Hydrogen: Linear Stark effect for n=2 states, unperturbed vs. perturbed basis, induced dipole moment | Pages 29 - 35 | Chapter 7 Problems | 5.2.1 Linear Stark Effect |
| Fine Structure of Hydrogen: Relativistic kinetic energy correction, Spin-Orbit coupling derivation from rest frame, Darwin term, total energy shift | Pages 35 - 48 | 7.3 The Fine Structure of Hydrogen | 5.3.1 / 5.3.2 Spin-Orbit Interaction and Fine Structure |
| Aharonov-Bohm Effect: Particle on a ring with magnetic flux, quasi-degeneracy at half-integer flux quanta | Pages 48 - 50 | 4.5.2 The Aharonov-Bohm Effect | 2.7.4 The Aharonov-Bohm Effect |
| Jaynes-Cummings Model: Two-level atom interacting with a quantized EM mode, detuning, resonance, coupled states | Pages 50 - 52 | Not Covered | 5.5.3 Time-Dependent Two-State Problems (Loosely related) |
| Zeeman Effect: Weak, strong, and intermediate magnetic fields, Landé g-factor, paramagnetic vs. diamagnetic terms | Pages 52 - 62 | 7.4 The Zeeman Effect | 5.3.3 The Zeeman Effect |
| Quantum Dynamics & Pictures: Time-evolution operator, Schrödinger picture, Heisenberg picture, Interaction (Dirac) picture | Pages 63 - 65 | Not Covered Formally | 2.2.2 / 5.5.2 The Interaction Picture |
| Time-Dependent Perturbation Theory (TDPT): Dyson Series, first-order transition probability, constant and harmonic perturbations | Pages 65 - 68 | 11.2 Emission and Absorption of Radiation | 5.7.1 Dyson Series / 5.7.2 Transition Probability |
| Magnetic Resonance & Rabi Oscillations: Time-dependent two-level systems, Kicked oscillator, Rotating Wave Approximation (RWA) | Pages 68 - 76 | 11.1.3 Sinusoidal Perturbations | 5.5.3 / 5.5.4 Spin Magnetic Resonance |


---

### Study Guide
1. **The Operator Foundations (Read Sakurai)**
* **Where to read:** Sakurai 2.3 (Simple Harmonic Oscillator).
*  **Why:** Your professor relies heavily on Dirac notation (bras and kets) and ladder operators. Griffiths uses wavefunctions (integrals) too much. Sakurai will teach you how to manipulate  and  algebraically, which is exactly how your professor solves the Morse potential and perturbed oscillator.

2. **Static Tweaks & Real Atoms (Read Griffiths)**
* **Where to read:** Griffiths Chapter 7 (7.1 through 7.4).
* **Why:** When it comes to the Hydrogen atom (Fine Structure, Zeeman, Stark), Sakurai can be incredibly dense. Griffiths walks through the exact derivations your professor did for Spin-Orbit coupling, the relativistic correction, and the Darwin term. Read Griffiths to understand the physics of these corrections, then look at your notes to see how your professor wrote the matrices.

3. **The "Pictures" of Quantum Mechanics (Read Sakurai)**
* **Where to read:** Sakurai 2.2.2 (Schrödinger vs. Heisenberg) and 5.5.2 (The Interaction Picture).
* **Why:** Griffiths completely ignores this, but it's on pages 63-65 of your notes. You *must* understand the Interaction Picture to do Time-Dependent Perturbation Theory. Sakurai explains this beautifully.

4. **Step 4: Things Changing Over Time (Read Sakurai & Notes)**
* **Where to read:** Sakurai 5.5.3, 5.5.4 (Magnetic Resonance) and 5.7.1 (Dyson Series).
* **Why:** Your notes on the Kicked Oscillator, Rotating Wave Approximation (RWA), and Rabi Oscillations are advanced. Sakurai handles two-state time-dependent problems with the exact same rigor as your professor.
* **A Note on the Jaynes-Cummings Model:** Pages 50-52 of your notes cover this. Neither book covers this specific model well because it belongs to *Quantum Optics*. I recommend studying this purely from your notes. It's just a specific application of a two-level system matrix diagonalization, so once you master Sakurai 5.1.2 (The Two-State Problem), the Jaynes-Cummings math will make perfect sense.
---

## FCH Summary

**Course Content**
- Time-independent perturbation theory: 
    - non-degenerate and degenerate perturbation
    - Fine structure of hydrogen atom, 
    - Stark effects
    - Zeeman effect
- Time-dependent perturbation theory: 
    - interaction picture
    - two-state problems
    - Dyson series
    - Fermi’s Golden rule
- Introduction to Scattering cross-section
- Lippman-Schwinger equation
- Born approximation
- Optical theorem
- Method of partial waves: 
    - free spherical waves
    - plane waves in terms of spherical waves
    - impact parameter
    - phase shifts
- Absorption & Induced emission of radiation
- electric diploe transition
- Landau levels
- Klein-Gordon equation
-  Dirac equation

**Suggested books:**
- Modern Quantum Mechanics by J. J. Sakurai
- Introduction to Quantum Mechanics by D. J. Griffithis
- Principles of Quantum Mechanics by R. Shankar
- Quantum Physics by S. Gasiorowicz
