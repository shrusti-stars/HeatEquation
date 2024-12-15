# PDE-Simulation-and-Compression

A numerical simulation project to solve the 1D heat equation and apply dimensionality reduction techniques using **PCA** for data compression. This repository is a comprehensive demonstration of solving Partial Differential Equations (PDEs) numerically and validating the effectiveness of data compression techniques.

---

## Features

1. **Numerical Simulation**:
   - Solves the **1D heat equation** using the **finite difference method** (FDM).
   - Simulates temperature distribution over time in a rod with defined initial and boundary conditions.

2. **Dimensionality Reduction**:
   - Applies **Principal Component Analysis (PCA)** to compress simulation data.
   - Validates compression quality with reconstruction error metrics like Mean Squared Error (MSE).

3. **Visualization**:
   - Plots:
     - Temperature evolution over time.
     - Original vs. Reconstructed data.
     - Compression error over time.

---

## Getting Started

### Prerequisites

- Python 3.x
- Required Libraries:
  - `numpy`
  - `matplotlib`
  - `scikit-learn`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shrusti-stars/PDE-Simulation-and-Compression.git
   cd PDE-Simulation-and-Compression
