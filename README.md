#  Fury Friends Sales Analysis

This project explores and analyzes sales data from **Fury Friends**, a pet store chain.  
The main goal is to understand **profitability patterns**, **store performance**, and **pet popularity**, using Python and popular data visualization libraries. 

---

##  Project Overview

1. **Data Loading & Cleaning**
   - Loaded the dataset from Excel (`Fury_Friends data set_4376.xlsx`).  
   - Checked data types, missing values, duplicates, and basic statistics.  
   - Filled missing numerical values with **mean values**.  
   - Removed duplicate rows.  
   - Converted categorical columns (`Pet` and `Area`) to proper **category types**.  
   - Saved a cleaned version of the dataset.

2. **Exploratory Data Analysis (EDA)**
   - **Profit by Store Area & Pet Type**: Bar charts show which pets generate the most profit in each store.  
   - **Total Profit per Store**: Highlighted the most profitable store.  
   - **Cost, Revenue, and Profit Trends by Store**: Line plots visualize the three metrics side by side.  
   - **Monthly Profit Trends**: Interactive Plotly line chart to track monthly profit.  
   - **Profit Distribution by Pet Type**: Pie chart shows each pet’s contribution to total profit.  
   - **Units Sold vs Profit**: Scatter plots reveal the relationship between sales volume and profit.  
   - **Heatmap of Profit by Area & Pet**: Quickly see which combinations of store and pet are most profitable.

3. **Insights & Highlights**
   - **Most profitable store:** Dudley with €692,497.43 in total profit.  
   - Cats and dogs are the leading contributors to overall profit.  
   - Monthly trends highlight seasonal fluctuations in sales.  
   - The relationship between units sold and profit varies by pet type, revealing sales efficiency differences.

---

##  Tools & Libraries
- **Python** 
- **Pandas & NumPy** (data manipulation)  
- **Matplotlib & Seaborn** (2D visualizations)  
- **Plotly Express** (interactive plots)  

---

