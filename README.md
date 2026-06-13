# Statistical Learning — Breast Cancer Analysis

This repository contains a Jupyter notebook that performs feature selection, regularized regression, decision tree modeling, and ensemble methods on a breast cancer dataset.

Files
- [data_analysis.ipynb](data_analysis.ipynb) — Main analysis notebook. Key notebook symbols:
  - [`fit_linear_reg_reduced`](data_analysis.ipynb)
  - [`forward_stepwise_selection`](data_analysis.ipynb)
  - [`backward_stepwise_selection`](data_analysis.ipynb)
  - [`grid_search`](data_analysis.ipynb)
- [data.csv](data.csv) — Dataset used by the notebook.
- [requirements.txt](requirements.txt) — Python dependencies.
- [stat_learning/](stat_learning/) — Local virtual environment and helper binaries (activate via `stat_learning/bin/activate`).

Quick start
1. Create and activate a virtual environment (optional if using the provided venv):
   - source stat_learning/bin/activate
2. Install dependencies:
   ```sh
   pip install -r requirements.txt