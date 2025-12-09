# Practical Assignment 12: Stochastic vs. Deterministic Models

This assignment contrasts two fundamental modeling approaches by implementing a stochastic sampling algorithm and a deterministic differential equation model.

## Objectives
* **Part A (Stochastic):** Implement the **Metropolis Algorithm** (MCMC) from scratch to sample from a complex distribution (e.g., Bimodal Mixture), demonstrating how randomness can estimate probability densities.
* **Part B (Deterministic):** Implement the **SIR (Susceptible-Infected-Recovered) Model** using Ordinary Differential Equations (ODEs) to simulate the predictable trajectory of an infectious disease.

## Libraries Used
* **Numpy:** Random number generation for the Metropolis step.
* **Scipy.integrate:** `odeint` for solving the SIR differential equations.
* **Matplotlib:** Visualizing the MCMC traces and the SIR epidemic curves.