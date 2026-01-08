# Interactive Option Strategy Builder & Simulator

An interactive Python-based tool for building option strategies (like Straddles) and simulating their performance using Monte Carlo methods.

## Features
- **Payoff Visualization**: Dynamically plot payoffs for individual and combined option legs.
- **Monte Carlo Simulation**: Uses Geometric Brownian Motion (GBM) to simulate 12,000+ price paths to calculate:
  - Expected Value (EV)
  - Probability of Profit/Loss
  - Median Payoff
- **Interactive Widgets**: Adjust spot price, strike, volatility, and time-to-expiry using sliders to see real-time changes in strategy metrics.
- **Analytics**: Automatic calculation of break-even points.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- SciPy
- Pandas

## How to Use
1. Clone the repository.
2. Open the `.ipynb` file in Jupyter Notebook or Google Colab.
3. Run the cells to launch the interactive simulator.
