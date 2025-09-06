# Apache Spark Homework – Notebooks Overview

Short descriptions of each notebook, for quick browsing on GitHub.

## Files

- **HW_Spark_WordCount.ipynb** — Classic Word Count example with PySpark RDD/DataFrame APIs: text ingestion, tokenization, stopword handling (if used), and term frequency aggregation.
- **HW_Spark_SQL.ipynb** — Spark SQL basics: creating DataFrames, registering temp views, and running `SELECT`, filtering, grouping, and joins using SQL and the DataFrame API.
- **HW_Spark_Clustering.ipynb** — Unsupervised learning with Spark ML (e.g., K‑Means/others): feature assembly, scaling, model fitting, and cluster evaluation/visualization.
- **HW_Spark_ML_Regression.ipynb** — Regression pipeline with Spark ML: VectorAssembler, train/validation split, model training (e.g., Linear/GBT/RandomForest Regressor), and metrics (RMSE/MAE/R²).
- **HW_Spark_Diabetes_Prediction.ipynb** — End‑to‑end classification workflow (diabetes prediction): data cleaning, feature engineering, model training (e.g., Logistic/Tree‑based), and evaluation (AUC/accuracy/precision‑recall).

## How to Run (quick start)

1. Install dependencies (example):
   ```bash
   pip install pyspark==3.5.1
   ```
2. Launch Jupyter and open a notebook:
   ```bash
   jupyter lab
   ```

> Tip: If a notebook uses external datasets, check the first cells for paths and update them as needed.

## Repo Structure (suggested)

```
.
├── data/                # optional: raw/processed datasets
├── notebooks/           # (or keep at repo root) the .ipynb files
└── README.md
```

