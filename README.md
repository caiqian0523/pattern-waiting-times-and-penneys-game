# Pattern Waiting Times and Penney's Game

A Python project analysing coin-pattern waiting times and competing
patterns using absorbing Markov chains and Monte Carlo simulation.

## Contents

### 1. Pattern Waiting Times

- Constructs prefix-based Markov states automatically
- Builds the absorbing transition matrix
- Solves \((I-Q)E=\mathbf{1}\) for exact expected waiting times
- Validates exact results through Monte Carlo simulation
- Visualises convergence and 95% confidence intervals

### 2. Penney's Game

- Models two competing coin-toss patterns
- Solves \((I-Q)p=r\) for exact absorption probabilities
- Compares exact probabilities with Monte Carlo estimates
- Produces a pairwise probability matrix for all length-three patterns

## Methods

- Absorbing Markov chains
- Linear systems
- Monte Carlo simulation
- Standard errors and confidence intervals
- Prefix and suffix state matching

## Technologies

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Notebooks

- `01_pattern_waiting_times.ipynb`
- `02_penneys_game.ipynb`

## Example results

For the pattern `HTTH`, the exact expected waiting time is 18.

For `HTH` competing against `HHT`,

\[
P(\text{HTH appears first})=\frac{1}{3}.
\]

Both exact results are validated through Monte Carlo simulation.
