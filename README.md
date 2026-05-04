# mlpredictions

Admission prediction pipeline and analysis in a single notebook.

## Project Contents
- AF_Futures_ML_Prediction_v2.ipynb: End-to-end pipeline (load, feature engineering, training, calibration, evaluation, and plots).
- cutoff_data_1000_rows.csv: Sample data used by the notebook.

## How To Run
1. Open the notebook in VS Code or Jupyter.
2. Ensure a Python environment with common data science packages is available.
3. Run the cells top to bottom.

## Notes
- The notebook trains and calibrates multiple models, then picks the best calibrated model.
- The final cell provides a sample prediction and chart for a user-provided rank.