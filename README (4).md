# Practical Work No. 4 — Aggregation and Grouping

**Author:** Andrii Melnykivskyi, group KN-41

## Description
This work covers grouping and aggregation in Pandas: `groupby` with `sum` / `mean` / `size` / `agg`, grouping by several columns, pivot tables (`pivot_table`), cross tabulations (`crosstab`), combining datasets with `concat`, `merge` and `join`, and computing analytical indicators by group (e.g. revenue share). It also includes answers to the self-check questions and a bonus task with a custom two-table dataset.

## Dataset
`sales.csv` — a training dataset of coffee shop sales (800 transactions, March–April 2024) with 6 columns: `date`, `datetime`, `cash_type`, `card`, `money`, `coffee_name`.

## Files
- `Melnykivskyi_Lb4.ipynb` — practical part (steps 1–10)
- `Zavdannya4_Melnykivskyi.ipynb` — individual tasks 1–7 and answers to the self-check questions
- `Dodatkove4_Melnykivskyi.ipynb` — bonus task ★ (custom `products` and `orders` tables)
- `sales.csv` — dataset
- `results/` — CSV results of the bonus task

## How to run
1. Upload `sales.csv` to your Google Drive (the `MyDrive` folder).
2. Open a notebook in Google Colab.
3. Run the cells in order; allow access to Google Drive when prompted.

Outside Colab, the notebooks fall back to the local files in the same folder.

## Requirements
Python 3, `pandas`, `numpy` (preinstalled in Google Colab).
