# Pharmaceutical Sales EDA

Exploratory data analysis of daily sales across 8 drug categories from a real pharmacy in Serbia (2014–2019).

**Dataset:** [Pharma Sales Data — Kaggle](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data) by Milan Zdravkovic  
**Records:** 2,106 days · 8 drug categories (ATC classification)

## What's inside

The notebook covers:
- Total sales by drug category — Paracetamol (N02BE) makes up ~48% of all sales
- Weekday and monthly seasonality — winter peaks, summer dips
- Year-over-year trend (2015–2018 full years)
- Drug correlation heatmap — which categories move together
- Top 10 busiest days and a weekday × month heatmap

## Setup

```bash
git clone https://github.com/your-username/pharma-sales-eda.git
cd pharma-sales-eda
pip install -r requirements.txt
```

Place `salesdaily.csv` inside the `data/` folder, then open the notebook:

```bash
jupyter notebook notebooks/pharma_sales_EDA.ipynb
```

Charts are saved to `outputs/charts/` when you run all cells.

## Project structure

```
pharma-sales-eda/
├── data/
│   └── salesdaily.csv
├── notebooks/
│   └── pharma_sales_EDA.ipynb
├── outputs/
│   └── charts/            # auto-created on run, git-ignored
├── requirements.txt
└── .gitignore
```
