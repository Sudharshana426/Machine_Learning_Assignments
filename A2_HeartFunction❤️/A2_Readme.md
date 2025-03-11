# Heart Curve Generator and Plotter

## Overview
This project generates and plots a heart-shaped curve using two different methods:

1. **Parametric Equations**: Uses trigonometric functions to calculate x and y coordinates.
2. **Explicit Formula**: Uses a mathematical expression to calculate y values for given x values.

The curves are visualized on a 2D plot for comparison.

---

## How the Curves are Generated

### Method 1: Parametric Equations
The heart curve is defined using the following equations:
- `x = 16 * sin(t)^3`
- `y = 13 * cos(t) - 5 * cos(2t) - 2 * cos(3t) - cos(4t)`

Here, `t` is a parameter that ranges from `0` to `2π`.

### Method 2: Explicit Formula
The heart curve is defined using the following equations:
- `y = sqrt(1 - x^2) + |x|^(2/3)`
- `y = -sqrt(1 - x^2) + |x|^(2/3)`

Here, `x` ranges from `-1` to `1`.

---

## Features
- Generates heart-shaped curves using two different mathematical approaches.
- Visualizes both curves on a single plot for comparison.
- Easy-to-understand implementation using Python and Matplotlib.

---

## Requirements
- Python 3.x
- NumPy
- Matplotlib

---

## Installation
Install the required libraries using pip:

```bash
pip install numpy matplotlib
