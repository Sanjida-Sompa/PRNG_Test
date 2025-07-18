Custom PRNG Analysis
Project Overview
This project focuses on building a custom pseudorandom number generator (PRNG) using a basic method and evaluating its performance. The custom PRNG is visually and statistically compared with NumPy’s built-in random number generator to assess randomness and uniformity.

Key Features
Scatter Plots
Visual comparison of point distribution between the custom PRNG and NumPy's generator

Helps detect patterns or clustering that indicate poor randomness

Histograms
Display the frequency distribution of X and Y values

Used to evaluate how close the outputs are to a uniform distribution

Summary Statistics
Mean and standard deviation calculated for both X and Y values

Allows direct comparison of the statistical properties of the two generators

 How to Run
Install Python (version 3.7 or above)

Install required libraries:
pip install numpy matplotlib

Run the script:
python src/prng_analysis.py

Output Includes
Two scatter plots saved as custom_vs_numpy_prng.pdf

Four histograms saved as custom_prng_histograms.pdf

Console output with mean and standard deviation of X and Y values

Learning Outcomes
Understand the behavior and limitations of simple PRNGs

Learn how to evaluate random number generators using visual tools and statistics

Compare a custom-built generator to a standard, reliable library implementation
