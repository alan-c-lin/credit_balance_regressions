# Exploring Credit Balance with Linear and Polynomial Regression

This project explores the `Credit` dataset from the `ISLP` package to model and predict balance using linear and polynomial regression. The goal is to illustrate model fitting, coefficient analysis, p-value evaluation, and visualizations of regression results. All data is provided via the `ISLP` package; no external datasets are required.

## Project Structure

- `credit_balance_regressions.ipynb` — Main Jupyter notebook containing code and explanations.
- `credit_balance_regressions.html` — Exported HTML version of the notebook.
- `credit_balance_regressions.pdf` — Exported PDF version of the notebook.
- `figures/` — Contains exported plots mainly for reference; all key figures are already embedded in the outputs.

## Key Points

- Linear and cubic polynomial regressions performed on balance vs predictors.
- Coefficient comparisons made between single-variable and multiple-variable regressions.
- Significant p-values identified for cubic regression terms (α = 0.05).
- Scatterplots visualizing balance with fitted regression lines for linear and cubic models.

## Requirements

- Python (≥ 3.8)
- Jupyter Notebook / Jupyter Lab
- Python packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `ISLP`

You can install the required packages using: `pip install pandas numpy matplotlib seaborn statsmodels ISLP`

## How to Use

1. Clone or download this repository.
2. Open `credit_balance_regressions.ipynb` in Jupyter Notebook or Jupyter Lab.
3. Run all cells to reproduce results, figures, and exported HTML/PDF outputs.