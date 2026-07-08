# Artificial Neural Networks for Logic Gates

This repository explores the fundamentals of Artificial Neural Networks (ANN) and Perceptrons by implementing basic logic gates from scratch. It documents the progressive shift from iterative scalar implementations to vectorized matrix operations, and finally to scaled architectures handling multiple inputs.

## 📂 Repository Structure

The project is structured into three progressive Jupyter Notebooks:

* **`1.Basic Implementation.ipynb`** An introductory, step-by-step implementation of basic 2-input logic gates (e.g., AND, OR, NAND) using simple loops and scalar weight adjustments. Ideal for understanding the underlying math of step functions and single-layer perceptrons.
* **`2.Matrix Implementation.ipynb`** An optimized refactoring of the initial code that replaces loops with vectorized matrix operations using `NumPy`. This showcases efficient forward propagation and weight updating techniques common in production-level deep learning.
* **`3. 3 Input Gates Learning.ipynb`** An extension of the perceptron model designed to compute and learn truth tables for 3-input logical combinations, demonstrating how the model scales with increased feature dimensionality.

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the following libraries:
* `numpy`
* `jupyter`

### Installation & Running the Notebooks
1. Clone the repository:
   ```bash
   git clone https://github.com/Akshat120/logic-gates-from-scratch.git
   cd logic-gates-from-scratch
   ```
