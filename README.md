# Mall Customer Segmentation

An unsupervised learning notebook that explores customer demographics and purchasing behavior, then groups customers with K-Means.

**Technology:** Python · pandas · scikit-learn · Plotly · Matplotlib · Seaborn

## Features

- Explore age, income, gender, and spending-score distributions.
- Scale features before clustering.
- Compare cluster counts through elbow and silhouette analyses.
- Assign cluster labels and visualize customer segments.

## Repository guide

| Path | Purpose |
|---|---|
| [mall-customers-segmentation.ipynb](mall-customers-segmentation.ipynb) | EDA and K-Means experiments. |
| [Mall_Customers.csv](Mall_Customers.csv) | Customer dataset. |

## Requirements and current limitations

Change the Kaggle path to the included `Mall_Customers.csv` before running locally. Cluster identifiers are arbitrary model labels, and the resulting segments depend on the selected features, scaling, and cluster count.

There is no standalone application or deployed segmentation API in this repository.

## Getting started

```bash
git clone https://github.com/IbrahimAbdelsattar/Mall-Customer-Segmentation-.git
cd Mall-Customer-Segmentation-
```

Use a Python virtual environment:

```bash
python -m venv .venv
```

Activate it with `source .venv/bin/activate` on macOS/Linux or `.venv\Scripts\Activate.ps1` in PowerShell.

```bash
python -m pip install jupyter pandas numpy matplotlib seaborn plotly scikit-learn
python -m jupyter notebook
```

Open the notebook listed above and run its cells in order. Adjust dataset and model paths as described in the limitations section.
