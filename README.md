# Non-hermitian-lattice

Numerical simulation of a 1D non-Hermitian lattice with open boundary conditions, containing a central impurity.

## Project goal
Studying localization and eigenvalue behavior in a non-Hermitian system with open boundary conditions.

## Methods
- Python
- Numpy
- Numerical diagonalization
- Visualization with Matplotlib

## Results

### Eigenvalue spectrum
![Eigenvalues](Eigenvalues_plot.png)

### Localization behavior
![Localization](Localization_plot.png)

### Impurity density relation
![Density](density_impurity_linear_relation.png)

## Files

analysis notebook: NHimpurity_OBC_notebook.ipynb
plots: generated numerical results

jupyter nbconvert Non_Hermitian_impurity_analysis.ipynb --to html
