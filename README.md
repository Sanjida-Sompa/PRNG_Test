Custom Pseudorandom Number Generator (PRNG) Analysis
Project Overview
This project implements a custom Pseudorandom Number Generator (PRNG) using the Linear Congruential Generator (LCG) algorithm. The PRNG is evaluated for its uniformity and statistical behavior by comparing it with NumPy's built-in uniform random number generator.

Algorithm Used: Linear Congruential Generator (LCG)
The LCG generates the next random number using the formula:

Xₙ₊₁ = (a * Xₙ + c) mod m

Where:

a is the multiplier
c is the increment
m is the modulus
X₀ is the seed (initial value)
Features & Visualizations
Scatter Plots:

Compares the custom PRNG and NumPy’s PRNG output in 2D space.
Evaluates randomness and point distribution.
Histograms:

Shows the distribution shape of X and Y values.
Helps assess how uniform or skewed the PRNG output is.
Summary Statistics:

Calculates mean and standard deviation of X and Y values.
Verifies the closeness to a uniform distribution.
How to Run
Make sure Python is installed (Python 3.7+ recommended).
Install required packages:
pip install numpy matplotlib Run the script:

python src/prng_analysis.py This will:

Generate scatter plots

Show histograms

Print statistical summaries to the terminal

Learning Outcomes Understand how LCG works.

Analyze and visualize random number uniformity.

Compare custom PRNG with standard library generators.
