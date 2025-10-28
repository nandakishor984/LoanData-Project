# Loan Data Project

This repository contains a guided example notebook and supporting CSV/checkpoint files for exploring loan data using NumPy (and other common Python data tools).

Contents
- `A-Loan-Data-Example-with-NumPy-Complete.ipynb` — the main analysis notebook demonstrating loading, preprocessing, and exploring the loan dataset with NumPy.
- `loan-data.csv` — raw loan dataset used in the notebook.
- `loan-data-preprocessed.csv` — a preprocessed/cleaned version of the dataset (if present).
- `EUR-USD.csv`, `Checkpoint-Numeric.npz`, `Checkpoint-Strings.npz`, `checkpoint-test.npz` — auxiliary files referenced by the notebook (currency history and NumPy checkpoints).

Purpose
This project demonstrates practical, reproducible data exploration and preprocessing for loan/financial datasets, with an emphasis on using NumPy for efficient array operations and checkpoints for reproducible intermediate results.

How to run
1. Open the notebook in Jupyter or VS Code (Jupyter extension).  
2. Ensure required packages are installed (example for PowerShell):

```powershell
python -m pip install --upgrade pip; \
python -m pip install numpy pandas matplotlib seaborn jupyter
```

3. Run the notebook cells sequentially. If checkpoint `.npz` files are present, the notebook may load them to skip long preprocessing steps.

Suggested workflow
- Inspect `loan-data.csv` to understand columns and missing values.
- Run the preprocessing cells to generate `loan-data-preprocessed.csv`.
- Re-run analysis and visualizations on the preprocessed file.

Notes
- This repository is aimed at educational/demo use. For production or modeling experiments, add a requirements manifest (e.g., `requirements.txt`), tests, and versioned data handling.

