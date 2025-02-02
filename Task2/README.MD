# DATA ANALYSIS TASK - 2  

## Overview  
This repository contains solutions for **Task 2** divided into two sub-tasks:  
- **Task 2.1**: General Exploratory Data Analysis (EDA)  
- **Task 2.2**: Sales Performance Analysis  

---

## Task 2.1: General EDA  
### Objective  
Perform exploratory data analysis to identify trends, patterns, anomalies, and factors influencing performance.  

### Steps Included  
1. **Data Cleaning**  
   - Handle missing values.  
   - Remove duplicates.  
   - Detect and remove outliers using IQR.  
2. **Statistical Analysis**  
   - Summary statistics (mean, median, std, etc.).  
   - Correlation matrix.  
3. **Visualizations**  
   - Histograms, boxplots, and heatmaps.  

### Deliverables  
- Cleaned dataset (`cleaned_dataset.csv`).  
- Statistical summaries and correlation analysis.  
- Visualization plots (distributions, outliers, correlations).  

---

## Task 2.2: Sales Performance Analysis  
### Objective  
Analyze sales data to identify trends, relationships, and factors affecting sales performance.  

### Steps Included  
1. **Data Cleaning**  
   - Handle duplicates and missing values.  
   - Convert `Order Date` to datetime format.  
2. **EDA & Visualizations**  
   - Time series plot for sales trends.  
   - Scatter plot (Profit vs. Discount).  
   - Sales distribution by Region/Category.  
3. **Predictive Modeling**  
   - Linear Regression model to predict Sales using Profit and Discount.  
   - Model evaluation with R² score and MSE.  

### Deliverables  
- Visualizations (time series, scatter plots, bar/pie charts).  
- Trained predictive model.  
- Actionable insights (e.g., optimal discount rates, top regions).  

---
## How to Use This Repository  
### Prerequisites  
- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- [Datasets](https://github.com/yannie28/Global-Superstore/tree/master):  
  - `GlobalSuperstore.csv` (for Task 2.1)
  - `sales_data.csv` (for Task 2.2)  

### Instructions  
1. **Clone the repository**  
   ```bash
   git clone [your-repository-url]
   