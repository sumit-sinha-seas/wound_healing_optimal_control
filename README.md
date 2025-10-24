# Wound healing Optimal Control

This repository contains numerical simulations for wound healing using optimal control. The simulations are implemented in JAX and explore two different scenarios: one with experimental constraints and one without.

## Files

*   `oc_wound_healing_experimentally_constrained.ipynb`: Jupyter notebook for the optimal control simulation of wound healing with experimental constraints. This notebook includes the optimization process and visualization of the results.
*   `oc_wound_healing_experimentally_unconstrained.ipynb`: Jupyter notebook for the optimal control simulation of wound healing without experimental constraints. This notebook also includes the optimization process and visualization of the results.
*   `LICENSE`: The license for this project.
*   `.gitignore`: A file specifying intentionally untracked files to be ignored by Git.
*   `README.md`: This file.

## Dependencies

The following Python libraries are required to run the simulations:

*   `jax`
*   `jaxlib`
*   `optax`
*   `numpy`
*   `matplotlib`

## Usage

The Jupyter notebooks can be run in a suitable environment like Google Colab or a local Jupyter installation with the required dependencies installed. To run the simulations and see the results, open one of the notebooks and execute the cells in order.