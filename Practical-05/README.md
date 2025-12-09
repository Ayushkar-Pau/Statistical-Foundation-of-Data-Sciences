# Practical Assignment 5: Probability & Hypothesis Testing

This assignment focuses on calculating empirical probabilities from the **Teacher Rating Dataset** and performing a standard **Two-Tailed Z-Test** to compare sample means against a known population.

## Objectives

1.  **Probability Calculation:**
    * Calculating the probability of an instructor receiving an evaluation score **greater than 4.5**.
    * Calculating the probability of receiving a score **between 3.5 and 4.2**.
2.  **Hypothesis Testing (Z-Test):**
    * Analyzing a basketball team scenario (Sample: $n=36$, $\bar{x}=10.7$ vs. Population: $\mu=12$, $\sigma=5.5$).
    * Formulating the **Null Hypothesis ($H_0$)** (Regional mean is equal to historic mean) and **Alternative Hypothesis ($H_a$)** (Means are different).
    * Performing a two-tailed test to determine statistical significance.

## Libraries Used
* **Pandas:** Calculating probabilities based on dataset frequencies.
* **Scipy.stats:** Using `norm.cdf` or manual calculations for Z-scores and p-values.
* **Math:** Calculating the standard error.