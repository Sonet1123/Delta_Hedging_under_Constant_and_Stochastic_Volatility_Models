# Delta Hedging under Constant and Stochastic Volatility Models
This project implements and evaluates delta hedging strategies for European call options under both constant volatility (Black-Scholes) and stochastic volatility (Heston and GARCH) models. The goal is to study hedging performance and compare various approaches, including analytical, Monte Carlo-based, and model-consistent delta estimators.

## Modules

###  Module 1: Black-Scholes Delta Hedging
- Analytical delta with daily rebalancing.
- Performance evaluated in terms of hedging error distribution.

### Module 2: Transaction Cost Analysis
- Introduces proportional transaction costs.
- Evaluates impact of hedging frequency on error and cost trade-off.
- Finds optimal hedge frequency under different penalty weights (λ).

###  Module 3: Monte Carlo Delta Hedging
- Estimates deltas via finite-difference Monte Carlo pricing.
- Compares hedging performance with analytical Black-Scholes deltas.

### 🌪️ Module 4: Stochastic Volatility Models
- Delta hedging under **Heston** and **GARCH(1,1)** models using:
  - Black-Scholes delta
  - Pathwise volatility delta
  - Constant model-consistent delta (FD)
  - Dynamic model-consistent delta (FD)

##  Evaluation Metrics
- Mean Hedging Error
- Standard Deviation of Error
- Max Loss / Max Gain
- Comparison of hedging error distributions

## Technologies
- Python, NumPy, Matplotlib, pandas
- Monte Carlo simulation
- Finite-difference estimation
- Option pricing under SV models

##  Files
- `main.ipynb`: Jupyter notebook with all modules.
- `README.md`: This file.
- 'delta_hedging.pdf' : pdf report 

##  Outcome
This project demonstrates how various modeling choices affect hedging performance and highlights the trade-offs between model complexity and hedging precision.


