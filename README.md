# Optimization Exercises with Gurobi

This repository contains three small operations-research exercises implemented with Gurobi. I completed them while studying decision making and mathematical optimization.

## Included notebooks

- `transportation_prob1.ipynb` — a transportation model with factory capacities and store demand
- `transportation_prob2.ipynb` — a second formulation of the transportation problem
- `cashflows.ipynb` — a multi-period cash-allocation model

Each notebook writes the decision variables, objective, and constraints directly in Python so the mathematical model can be followed alongside the solver code.

## Requirements

- Python and Jupyter
- NumPy
- `gurobipy`
- a working Gurobi licence

## Running the exercises

Open a notebook and run its cells in order. These are self-contained teaching examples with small, fixed inputs; edit the data in the notebook if you want to test another scenario.

## Note

The models demonstrate formulation and solver use. They are not a complete supply-chain planning system.
