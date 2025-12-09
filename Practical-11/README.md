# Practical Assignment 11: Bayesian Inference & MCMC

This assignment explores **Bayesian Statistics** by modeling historical sunspot data (1749-2018) using a **Gamma Distribution** and estimating its parameters via the **Metropolis-Hastings Algorithm** (implemented from scratch).

## Objectives
1.  **Time Series Visualization:** Plotting the "Monthly Mean Total Sunspot Number" to observe the 11-year solar cycle.
2.  **Probabilistic Modeling:** Fitting a Gamma distribution ($y \sim \Gamma(\alpha, \beta)$) to the sunspot count data, which is non-negative and skewed.
3.  **MCMC Implementation:** Implementing the **Metropolis-Hastings** sampler to estimate the posterior distributions of the shape ($\alpha$) and rate ($\beta$) parameters.
4.  **Convergence Analysis:** Visualizing trace plots, removing "burn-in" samples, and plotting posterior histograms.
5.  **Prediction:** Calculating the expected parameters for different time periods (First 50 samples vs. All vs. Last 50).

## Libraries Used
* **Pandas:** Loading the SIDC sunspot dataset.
* **Scipy.stats:** Computing the Log-Likelihood using the Gamma PDF.
* **Matplotlib/Seaborn:** Visualizing the traces and posterior distributions.