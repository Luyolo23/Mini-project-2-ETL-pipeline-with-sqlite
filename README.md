# Mini Project 2 — ETL pipeline with SQLite

This repository contains a small ETL (Extract, Transform, Load) demonstrator using a Jupyter notebook and SQLite. It ingests sales data from a CSV file, performs transformations/cleaning inside a notebook, and shows how to store/query the result using SQLite.

## Files

- `etl_sales.ipynb` — Jupyter notebook implementing the ETL steps (extract from CSV, transform with pandas, load into SQLite). 
- `sales_data.csv` — Sample sales data used by the notebook.
- `README.md` — This file.

## Requirements

- Python 3.8+ (3.10 or later recommended)
- Jupyter (notebook or lab)
- pandas
- sqlite3 (standard library)


## Quick setup

1. Install required Python packages:

   ```bash
   pip install --upgrade pip
   pip install jupyter pandas
   ```

   If you prefer JupyterLab:

   ```bash
   pip install jupyterlab
   ```

## How to run

1. Start the Jupyter server at the repository root:

   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```

2. Open `etl_sales.ipynb` in your browser.
3. Run the notebook cells sequentially. The notebook reads `sales_data.csv`, performs cleaning/transformation, and demonstrates storing and querying the results in a SQLite database (created in the notebook). 
