# Stochastic Loop Formation: Analytical and Simulated Study

### Overview  
This project models a process in which pairs of string ends are tied together at random. Over successive iterations, these pairings form either loops or chains. The goal is to explore the probabilistic structure of loop formation, including expected number of loops, loop-length probabilities, and the limiting behaviour of the system. This is done using both mathematical derivations and Monte Carlo simulations.

---

### Key Questions Addressed

- What is the expected number of loops formed after k tying sessions, starting from N strings?
- What is the probability of forming a loop of length exactly N?
- How are loops of different lengths distributed after k ties?
- What is the expected number of loops of length 1?
- How does imposing structural restrictions (e.g. top-bottom matching) affect the outcomes?

---

### Methods Used

Mathematical Approach
- Defined recursive expectations using custom-defined random variables. 
- Derived closed-form probabilities where tractable.
- Used combinatorial logic and conditional probability to form conjectures.

Simulation Approach (Python) 
- Created a simulation of the string-tying process.
- Verified analytic expressions against empirical results.  
- Visualised loop-length distributions and expected values using Matplotlib.

Validation
- Matched theoretical predictions with simulation (e.g. P[loop of length N] ≈ 0.0887)  
- Observed convergence in expectations as N → ∞.

---

### Files

| File | Description |
|------|-------------|
| `Stochastic_Loop_Formations.ipynb` | Python notebook for simulations and plots |
| `Stochastic Loop Formations.pdf` | Full write-up of mathematical derivations and conclusions |
