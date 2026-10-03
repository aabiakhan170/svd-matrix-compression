# Matrix Dimensionality Reduction & Image Compression via SVD

This project implements **Singular Value Decomposition (SVD)** using Python and NumPy to demonstrate data dimensionality reduction and image compression. 

As a Mathematics student specializing in **Numerical Methods and Numerical Analysis**, this repository serves as a practical implementation of structural linear algebra applied to data science problem-sets.

## Mathematical Core
An image can be represented as a matrix A of size m × n. SVD factorizes this matrix into three distinct matrices:

\[A = U \Sigma V^T\]

Where:
*   U is an m × m orthogonal matrix (Left singular vectors / Spatial structures)
*   Σ is an m × n diagonal matrix containing singular values (Eigenvalues sorted by variance magnitude)
*   \(V^T\) is an n × n orthogonal matrix (Right singular vectors)

By keeping only the top k singular values from Σ and discarding the rest, we compute a low-rank approximation of the matrix, effectively compressing the data size while preserving structural integrity.

## Key Features
*   **Framework-Free:** Built strictly using fundamental numerical matrices (`NumPy`) and data plotting (`Matplotlib`).
*   **Rank Adjustments:** Dynamically tests different values of k to track information retention versus compression ratios.
*   **Mathematical Demonstration:** Direct visual tracking of numerical decay in matrix features.

## How to Run
1. Clone this repository.
2. Ensure you have `numpy`, `matplotlib`, and `Pillow` installed.
3. Open `svd_matrix_compression.ipynb` in Jupyter Notebook and execute the cells.

## Author
*   **Name:** aabiakhan170
*   **Background:** B.Sc. Mathematics Student
