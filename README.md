# Probability Distribution Exercises with Python

![Preview](assets/preview.jpeg)

This repository contains a data science bootcamp assignment focusing on probability distributions using Python. The project demonstrates the implementation and visualization of binomial, normal, and uniform distributions using SciPy and matplotlib.

## Project Overview

The notebook `problems.ipynb` includes:

- **Binomial Distribution**: Implementation of probability mass function (PMF), cumulative distribution function (CDF), quantile function, and random number generation
- **Exercise 1**: A reusable `ContinuousDistribution` class for normal and uniform distributions
- **Visualizations**: Matplotlib plots showing probability density, cumulative density, and percentiles for each distribution type

## Getting Started

### Option 1: GitHub Codespaces (Recommended)

1. **Fork this repository** to your GitHub account
2. **Open in Codespaces**:
   - Navigate to your forked repository
   - Click the green "Code" button
   - Select "Codespaces" tab
   - Click "Create codespace on main"
3. **Wait for setup**: The codespace will automatically configure the environment using the `.devcontainer/devcontainer.json` configuration
4. **Run the notebook**: Open `problems.ipynb` and run all cells

### Option 2: Local Setup

1. Fork and clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook problems.ipynb
   ```

## Dependencies

The project requires the following Python packages (see `requirements.txt`):
- NumPy
- SciPy
- Matplotlib
- Jupyter

## Key Functions

### Binomial Distribution Functions
- `dbinom()`: Probability mass function
- `pbinom()`: Cumulative distribution function  
- `qbinom()`: Quantile function
- `rbinom()`: Random number generation

### Continuous Distribution Class
- `ContinuousDistribution`: Wrapper class supporting normal and uniform distributions with methods for probability density, cumulative density, and percentiles

## Output

The notebook generates probability calculations and visualizations showing the behavior of different probability distributions, helping to understand their statistical properties.
