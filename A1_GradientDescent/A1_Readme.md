# Linear Regression: Finding the Best Fit Line using Linear Search and Gradient Descent

## Overview
This project implements a simple linear regression model using Python and NumPy. The goal is to find the best-fit line for a given dataset using different optimization techniques, including linear search and gradient descent.

## Features
- Generates noisy linear data with a given slope and intercept.
- Visualizes the dataset and the true line.
- Computes the Mean Squared Error (MSE) loss function.
- Finds the best-fit slope using:
  - **Linear Search** (Brute-force approach)
  - **Gradient Descent** (Optimization algorithm)
  - **Recursive Global Minima Search** (Multiple runs of gradient descent to avoid local minima)

## Implementation Steps
1. **Generate Noisy Data**: Create a dataset based on a linear function with Gaussian noise.
2. **Plot the Data**: Visualize the noisy data and the true line.
3. **Loss Function Analysis**: Compute and plot the MSE loss for different slope values.
4. **Linear Search**: Iterate through possible slopes to find the one with the lowest loss.
5. **Gradient Descent**: Optimize the slope using gradient-based updates.
6. **Recursive Global Minima Search**: Run gradient descent multiple times with different starting points to avoid local minima.
7. **Comparison**: Evaluate which method performs best in minimizing loss.

## Results
- The project compares the efficiency of linear search vs. gradient descent.
- Gradient descent is expected to be more efficient, but multiple runs ensure avoiding poor local minima.

## Requirements
- Python 3.x
- NumPy
- Matplotlib

## How to Run
1. Clone the repository
2. Run the ipynb file in VS Code/ Google Colab/ Jupyter Notebook
3. View the plots and results in the console.

## Conclusion
This project provides an intuitive understanding of linear regression, optimization techniques, and the importance of choosing the right method to minimize loss effectively.

