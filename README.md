# Hydrogen Supply Chain Control Strategy Comparison

## Overview

This project presents a **comparative analysis** of two control strategies for optimizing the operation of a **solar-powered hydrogen supply chain**:

- **Model Predictive Control (MPC)**
- **Rule-Based Control (RBC)**

The supply chain system includes:
- Renewable electricity input (solar)
- Battery energy storage
- Hydrogen production via electrolysis
- Hydrogen storage and sales

## Objective

Evaluate and compare the performance of MPC and RBC strategies using a **Python-based simulation framework**, under identical time-varying conditions of:
- Solar availability
- Electricity pricing
- Hydrogen demand

## Methodology

### Model Predictive Control (MPC)
- Utilizes **forecasted disturbances** and **rolling-horizon optimization**.
- Allocates energy resources **cost-effectively** while respecting system constraints.

### Rule-Based Control (RBC)
- Uses **fixed heuristic rules**.
- Operates **reactively** without predictive capability.

## Key Findings

- **MPC**:
  - Achieves **higher cost-efficiency**.
  - Avoids **expensive grid electricity**.
  - Aligns production with demand.
  - Maximizes hydrogen utilization.

- **RBC**:
  - Simpler but **inefficient**.
  - Suffers from **overproduction** and **high energy waste**.
  - Incurs **financial losses** due to excessive grid usage.

- Both strategies show **limited battery engagement**, suggesting room for improvement in **battery dispatch strategies**.

## Conclusion

This study highlights the benefits of **predictive, optimization-based control** in managing hydrogen systems under uncertainty. It also establishes a baseline for **future research** in **adaptive, data-driven methods**, such as **reinforcement learning**, to further improve control performance.

---

*For more details, see the [full report](./report.pdf) or explore the [codebase](./src).*
