# Time-Series Forecasting Using Hybrid Quantum-Classical Models

This repository contains resources for experimenting with hybrid quantum-classical neural networks on time series forecasting tasks. The project couples a classical LSTM with a variational quantum circuit and compares its performance with a purely classical baseline.

## Contents
- `notebooks/hybrid_time_series_forecasting.ipynb` – end-to-end workflow covering data generation, preprocessing, model training, and evaluation. The notebook also includes an experiment that sweeps the quantum circuit depth.
- `reports/hybrid_forecasting_report.md` – concise report summarizing the experimental setup, modelling choices, insights, and recommended future work.

## Getting Started
1. Create and activate a Python 3.10 environment with internet access.
2. Install dependencies (PyTorch, PennyLane, scikit-learn, matplotlib, pandas, numpy). The notebook begins with installation commands for convenience.
3. Launch JupyterLab or Jupyter Notebook and open `notebooks/hybrid_time_series_forecasting.ipynb`.
4. Run the cells sequentially to reproduce the baseline and hybrid model experiments and compare their performance.

## Notes
- The repository uses a synthetic dataset for reproducibility. You can swap in any real-world time series by modifying the data preparation cells in the notebook.
- Due to the offline nature of the development environment, dependencies are not vendored in the repository. Ensure that required packages are available before executing the notebook.
