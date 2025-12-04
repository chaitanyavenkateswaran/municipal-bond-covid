# Volatility, Liquidity, and the COVID-19 Shock in U.S. Municipal Bond Markets

Replication code for the term paper:

> **Volatility, Liquidity, and the COVID-19 Shock in U.S. Municipal Bond Markets**  
> *An Empirical Analysis Using Panel Methods, Difference-in-Differences, VAR, Bayesian VAR, and Historical Decomposition*  
> Author: Chaitanya Venkateswaran  
> Geneva Graduate Institute, EI137 Topics in Econometrics, Fall 2025

This repository contains all scripts and notebooks required to reproduce the empirical results, figures, and tables in the paper.

---

**1. Overview**

The paper studies how market-wide volatility and liquidity shocks affected U.S. municipal bond returns during the COVID-19 crisis, and whether city-issued bonds were disproportionately affected compared to county-issued bonds.

Methodologically, the project uses:

- Issuer-level fixed effects and dynamic panel regressions,
- Difference-in-Differences (DiD) for City vs County around COVID,
- VAR (Vector Autoregression) for volatility–liquidity–returns dynamics,
- A conjugate Bayesian VAR (BVAR) with a Normal–Inverse-Wishart prior,
- Structural historical decomposition of returns around the COVID period.

All data are from the University of Chicago Center for Municipal Finance and related public sources.

---

**2. Repository Structure**

- README.md
- Main paper
- Appendix_math.pdf         # extended mathematical appendix
- Raw Data
  - city_bond_index.csv
  - county_bond_index.csv
  - school_bond_index.csv
  - muni_vix_data.csv
  - muni_liquidity.csv
- replication_notebook.ipynb
 
