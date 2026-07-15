# Profitability Analysis & Interactive Dashboard — Pet Retail (UK)

Sales and profitability analysis for **Fury Friends**, a UK pet store chain, identifying which stores, pet categories, and time periods drive the most profit.

## Key Insight

**Dudley** was the most profitable store, generating **€692,497.43** in total profit — with cats and dogs as the leading profit contributors across all locations.

## What I Did

1. **Data Cleaning**
   - Loaded and cleaned the raw sales dataset (missing values, duplicates, data types)
   - Filled missing numerical values with mean imputation
   - Converted categorical columns (`Pet`, `Area`) to proper category types

2. **Exploratory Analysis**
   - Profit by store area & pet type
   - Total profit per store (identifying the top performer)
   - Cost, revenue, and profit trends by store
   - Monthly profit trends (interactive Plotly chart)
   - Profit distribution by pet type
   - Units sold vs. profit (sales efficiency by pet category)
   - Heatmap of profit by area & pet combination

3. **Key Findings**
   - Dudley generated the highest total profit at €692,497.43
   - Cats and dogs are the leading contributors to overall profit
   - Monthly trends reveal seasonal fluctuations in sales
   - Units sold vs. profit relationship varies by pet type, exposing sales efficiency gaps between categories

## How to Run

```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl
jupyter notebook "Profitability Analysis and Interactive Dashboard for Pet Retail Stores in the UK.ipynb"
```

The dataset (`Fury_Friends data set_4376.xlsx`) is included in the repo.

## Tools

Python · Pandas · NumPy · Matplotlib · Seaborn · Plotly Express
