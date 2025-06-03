# Monte Carlo Simulation for Portfolio Risk Analysis

This project uses Monte Carlo simulation techniques to estimate the potential returns and risks associated with a financial investment portfolio. By simulating thousands of market scenarios, we can evaluate the probability distribution of outcomes and assess key risk metrics.

## 📊 Project Overview

Monte Carlo simulation is a powerful statistical tool used to model the probability of different outcomes in a process that cannot easily be predicted due to the intervention of random variables. In this project:

- We simulate portfolio returns over time using normally distributed random variables.
- Each simulation represents a possible future trajectory of an investment.
- Statistical analysis is performed to summarize the results.
- Risk metrics such as **expected value**, **standard deviation**, and **Value at Risk (VaR)** are calculated.

## 🔧 What I Did

- Built a Jupyter Notebook to run simulations of portfolio returns.
- Defined assumptions such as mean return, standard deviation, time horizon, and number of simulations.
- Implemented visualization tools (e.g., histograms, line plots) to display simulation outcomes.
- Computed and interpreted risk metrics to assess the likelihood of losses.
- Documented insights from the simulation to help guide investment decision-making.

## 📁 File Structure

- `montecarloproject.ipynb` — Main notebook containing all code, visualizations, and analysis.
- `README.md` — Project documentation (you are here).

## 🛠️ Dependencies

This project uses the following Python libraries:

- `numpy`
- `matplotlib`
- `pandas` (optional, for data handling)
- `seaborn` (optional, for advanced visualization)

Install them using:

```bash
pip install numpy matplotlib pandas seaborn
