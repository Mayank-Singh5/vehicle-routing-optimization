# Vehicle Routing Optimization
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mayank-Singh5/vehicle-routing-optimization/blob/main/Vehicle_Routing_Prob.ipynb)

Solving the **Vehicle Routing Problem (VRP)** using a custom Genetic Algorithm built with the Python `DEAP` library.

## Problem
Route a fleet of vehicles to visit a set of locations and return to a central depot, minimizing total distance traveled while balancing workload across vehicles.

## Features
- Custom evolutionary loop with **Elitism** and **Hall of Fame**
- **Ordered Crossover** and **Index Shuffling Mutation**
- Parameter sweeps: population size, mutation rate, tournament size
- Population diversity tracking over generations
- Dynamic route visualization with matplotlib

## Setup
```bash
pip install deap matplotlib numpy
```
> `random` and `statistics` are part of Python's standard library — no installation needed.

## Usage
Open the notebook in Google Colab:

1. Run all cells sequentially
2. `run_ga()` — runs the main GA and plots route snapshots
3. `run_experiments()` — runs parameter sweeps and diversity analysis

## Blog Post
Read the full writeup on Dev.to: [Solving a Logistics Problem Using Genetic Algorithms](https://dev.to/mayank_singh5/solving-a-logistics-problem-using-genetic-algorithms-2b33)

## Tech Stack
- Python, DEAP, NumPy, Matplotlib
