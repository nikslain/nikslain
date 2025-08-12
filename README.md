# Quickstart: EDA + Predictive Modeling

- Put your dataset into `/workspace/data/` (e.g., `/workspace/data/data.csv`).
- Open the notebook at `/workspace/notebooks/eda_modeling_clean.ipynb`.
- Configure `DATA_PATH` and `TARGET_COLUMN` in the first code cell.
- Run all cells top-to-bottom.
- Trained model and metrics will be saved to `/workspace/artifacts/`.

Optional environment variables:
- `DATA_PATH`: path to your dataset (default `/workspace/data/data.csv`)
- `TARGET_COLUMN`: target column name (default `target`)
- `ID_COLUMNS`: comma-separated ID columns to drop from features (default empty)
- `TASK_TYPE`: `classification`, `regression`, or `auto` (default `auto`)
