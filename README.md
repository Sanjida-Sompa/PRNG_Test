Custom Pseudorandom Number Generator (PRNG) Analysis
Project Overview
This project implements a Custom Pseudorandom Number Generator (PRNG) using the Linear Congruential Generator (LCG) method. The custom PRNG is analyzed and compared against NumPy’s built-in uniform PRNG to evaluate its quality in terms of randomness and statistical distribution.

 Algorithm: Linear Congruential Generator (LCG)
The Linear Congruential Generator is a classic method for generating sequences of pseudorandom numbers. It uses the following recurrence relation:

𝑋
𝑛
+
1
=
(
𝑎
⋅
𝑋
𝑛
+
𝑐
)
m
o
d
 
 
𝑚
X 
n+1
​
 =(a⋅X 
n
​
 +c)modm
🔧 Where:
𝑋
0
X 
0
​
 : Initial seed

𝑎
a: Multiplier

𝑐
c: Increment

𝑚
m: Modulus

Each generated number is then normalized to a floating-point value between 0 and 1 by dividing the output by 
𝑚
m.

Features & Visualizations
1. Scatter Plots
Displays the (X, Y) pairs generated from both the custom PRNG and NumPy’s uniform PRNG.

Helps visualize the spread and detect any repetitive patterns or clustering in the custom generator.

2. Histograms
Shows the distribution of generated X and Y values separately.

Useful to assess the uniformity of the output — ideally, a uniform distribution should have a flat histogram.

3. Summary Statistics
Calculates the mean and standard deviation for each set of values (X and Y).

These metrics indicate how closely the output matches a uniform distribution in the [0, 1) range:

Ideal mean ≈ 0.5

Ideal standard deviation ≈ 0.29

How to Run the Project
Prerequisites
Python 3.7 or higher

Install the required libraries:
pip install numpy matplotlib

Running the Script
Navigate to the project directory and run:
python src/prng_analysis.py
Output:
custom_vs_numpy_prng.pdf: Scatter plot comparison

custom_prng_histograms.pdf: Histogram visualization

Console output with statistical summary

Learning Outcomes
By completing this project, you will:

Understand how the Linear Congruential Generator (LCG) works

Learn how to build and use a simple custom PRNG

Gain experience in visualizing and statistically analyzing pseudorandom sequences

Recognize the limitations of basic PRNGs compared to standard library implementations
