# Cars24 Used Car Data Analysis (EDA)

**Author:** Parashuram Vaddekunta  
**GitHub:** [@parshuthebad](https://github.com/parshuthebad)

## Overview
This project explores the Cars24 used car dataset to understand how vehicle attributes—such as manufacturing year, kilometers driven, fuel type, transmission, and brand—influence selling prices. The analysis focuses on data inspection, quality checks, visual exploration, outlier detection, and feature correlation before building predictive models.

## Dataset
- **Source:** [Cars24 Combined Dataset](https://raw.githubusercontent.com/jatin5jan/CarPredict/main/cars_24_combined.csv)
- **Target Variable:** `Price`

## What This Notebook Covers
1. **Basic Dataset Details:** Inspects row/column dimensions, column names, data types, and separates numerical features from categorical features.
2. **Data Quality Checks:** Scans for missing values (with counts and percentages) and duplicate records.
3. **Summary Statistics:** Generates descriptive statistics and value counts for categorical variables.
4. **Univariate Analysis:** Visualizes feature distributions using histograms, KDE price plots, and category count plots.
5. **Outlier Detection & Skewness:** Identifies extreme values using boxplots and the Interquartile Range (IQR) method, and measures distribution skewness.
6. **Bivariate & Multivariate Analysis:** Evaluates feature relationships with `Price` using a correlation heatmap, scatter plots, category boxplots, and pairplots.
7. **Summary Report:** Prints key dataset metrics, price ranges, and the top features correlated with selling price.

## Files in This Repository
- `Cars24_EDA_Parashuram_Vaddekunta.ipynb` — Complete Jupyter Notebook containing the exploratory analysis and visualizations.

## Tools & Libraries Used
- **Python 3**
- **Pandas & NumPy** — Data loading, inspection, and statistical calculations
- **Matplotlib & Seaborn** — Data visualization and correlation heatmaps

## How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/parshuthebad/](https://github.com/parshuthebad/)<your-repo-name>.git
