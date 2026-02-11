# Statistical Learning Methods

A collection of Jupyter notebooks implementing fundamental statistical learning algorithms with mathematical explanations and visualizations.

## Contents

### [PCA.ipynb](PCA.ipynb) - Principal Component Analysis
- **Dataset**: Decathlon performance data
- **Implementation**: From-scratch PCA using eigenvalue decomposition
- Mathematical foundation and geometric interpretation
- Scree plot for component selection
- Correlation analysis between principal components and original variables
- Data standardization and covariance matrix computation

### [clustering.ipynb](clustering.ipynb) - K-Means Clustering
- **Dataset**: Synthetic 2D data with multiple clusters
- **Implementation**: Custom K-means algorithm with iterative optimization
- Visual demonstration of cluster formation dynamics
- Within-cluster variance convergence tracking
- Helper functions for centroid computation and label assignment

## Technologies

- Python 3
- NumPy
- Pandas
- Matplotlib

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/statistical-learning-from-scratch.git
cd statistical-learning-from-scratch

# Install dependencies
pip install numpy pandas matplotlib jupyter

# Launch Jupyter
jupyter notebook
```

## Features

- **Mathematical rigor**: Each notebook includes the theoretical foundation behind the algorithms
- **From-scratch implementations**: Algorithms built using NumPy rather than relying on sklearn
- **Visual insights**: Plots and visualizations to understand algorithm behavior
- **Educational focus**: Clear explanations suitable for learning and teaching

## Use Cases

These notebooks are ideal for:
- Understanding the mathematical foundations of ML algorithms
- Learning how to implement statistical methods from first principles
- Teaching materials for data science courses

## Background

This project demonstrates practical implementations of classical statistical learning techniques, emphasizing understanding over black-box usage of libraries.

