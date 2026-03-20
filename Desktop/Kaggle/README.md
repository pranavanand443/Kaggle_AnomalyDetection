# Tabular Sensor Anomaly Detection

This project contains a notebook to train tabular models on the provided sensor dataset and generate `submission.csv`.

## Files
- `anomaly_detection_notebook_v2.ipynb`: main end-to-end training + evaluation + submission notebook.
- `anomaly_detection_notebook.ipynb`: older variant (may be less stable).

## Data
The local Kaggle files are named `trainparquet.csv` and `testparquet.csv` but are actually Parquet (binary) files.

Notes:
- `trainparquet.csv` / `testparquet.csv` are ignored by Git via `.gitignore` to avoid committing large dataset artifacts.
- `submission.csv` is also ignored by Git (generated output).

## Run
Run the cells in `anomaly_detection_notebook_v2.ipynb` from top to bottom inside `Desktop/Kaggle/`.

