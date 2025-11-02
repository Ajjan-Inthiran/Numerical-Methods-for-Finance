# Numerical Methods for Finance

This repository presents a curated collection of numerical techniques widely used in quantitative finance, implemented and visualized in Python.  
Each notebook demonstrates a core mathematical method applied to derivative pricing, stochastic simulation, or partial differential equation (PDE) modeling, emphasizing accuracy, stability, and computational efficiency. The objective is to bridge theoretical finance with practical implementation to model price dynamics and evaluate complex instruments.

---

## Overview

This collection showcases the **key numerical engines** underlying modern quantitative finance:

| # | Notebook Title | Focus | Key Concepts |
|---|----------------|-------|---------------|
| **1** | *Heat Equation Simulation with Explicit Euler & Monte Carlo* | PDE foundations | Heat equation, finite difference schemes, explicit Euler discretization |
| **2** | *Tamed Euler Method for SDEs* | Stochastic processes | Euler–Maruyama, SDE stability, taming technique for drift control |
| **3** | *European Call Option Pricing: Binomial vs. Black-Scholes* | Discrete-to-continuous valuation | Risk-neutral valuation, convergence of binomial tree to Black–Scholes model |
| **4** | *American Put Binomial Tree Pricing and Early Exercise* | Optimal exercise features | Backward induction, early exercise boundary, tree convergence behavior |
| **5** | *Crank–Nicolson PDE Method for Barrier Options* | PDE methods for exotics | Crank–Nicolson discretization, boundary conditions for barrier options |
| **6** | *Up-and-Out Barrier Call Option Pricing* | Monte Carlo simulation | Path-dependent payoffs, barrier breach logic, pricing convergence |
| **7** | *Monte Carlo Pricing for Lookback Options* | Exotic path-dependent options | Continuous monitoring, payoff path dependency, simulation-based pricing |
| **8** | *Variance Reduction via Antithetic Variates* | Advanced variance reduction | Antithetic sampling, variance minimization, estimator convergence |
| **9** | *Variance Reduction via Control Variates* | Advanced variance reduction | Covariance adjustment, correlation exploitation, bias correction |

---

## Technical Highlights

Each notebook is written for **clarity, reproducibility, and quantitative rigor**, combining theoretical context with clean implementation.

**Key methods demonstrated:**
- **Binomial & Trinomial Trees:** Discrete lattice construction for European and American-style options; convergence analysis toward Black–Scholes prices.
- **Finite Difference Schemes:** Explicit Euler and Crank–Nicolson PDE solvers for diffusion-type option pricing equations.
- **Monte Carlo Simulation:** Randomized path generation, payoff averaging, and bias control for complex derivatives.
- **Variance Reduction:** Antithetic and control variates to improve estimator efficiency and reduce sampling noise.
- **Stochastic Differential Equations (SDEs):** Implementation of the *Tamed Euler scheme* to maintain numerical stability when simulating non-linear drifts.
- **Path-Dependent Payoffs:** Techniques for barrier and lookback options where payoff depends on the path history of the underlying.

---

## Practical Applications

These numerical methods are foundational in:

- **Derivative Pricing:** Computing fair values for vanilla and exotic contracts under various stochastic models.  
- **Risk Management:** Simulating portfolio exposures under diffusive dynamics.  
- **Quant Research & Strategy Development:** Understanding stochastic behavior of assets and developing pricing intuition.  
- **Model Validation:** Testing the numerical accuracy and convergence of pricing algorithms used in production trading systems.

---

## Technical Environment

All notebooks are written in **Python 3** and require the following packages:

numpy
scipy
matplotlib
