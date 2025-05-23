> **Disclaimer:** This project was originally conducted in Indonesian. For the purpose of publishing on GitHub, all content has been translated into English.
# Bike Sales Data Analysis

## Group Members
| **Student Name** | **Student ID**         |
|-------------|-----------------|
| Ardian Vega Carrelino | 215314161 |
| Prischia Ballo        | 215314166 |
| Putri Yohana Parhusip | 215314169 |

---

## Project Overview

This project presents an exploratory data analysis (EDA) of a comprehensive bike sales dataset. The main objectives are to understand sales trends, customer demographics, product performance, and to provide actionable business insights for inventory management, pricing, and marketing strategies.

---

## Workflow

1. **Data Loading & Cleaning**
    - Import libraries and load the dataset.
    - Remove unnecessary columns and handle missing values.
    - Detect and treat outliers using the Interquartile Range (IQR) method.

2. **Exploratory Data Analysis (EDA)**
    - **Univariate Analysis:** Analyze individual variables to understand their distributions.
    - **Bivariate Analysis:** Explore relationships between pairs of variables using visualizations and summary statistics.
    - **Multivariate Analysis:** Examine correlations among multiple variables using heatmaps and pairplots.

3. **Visualization**
    - Use bar plots, pie charts, box plots, and heatmaps to visualize key findings and trends.

4. **Insights & Conclusions**
    - Summarize key findings regarding sales trends, customer segments, product pricing, and correlations between variables.
    - Provide recommendations for business strategy based on the analysis.

---

## Key Insights

- **Sales Trends:** June is the peak month for sales; adults (35-64) are the primary buyers; the United States leads in sales volume.
- **Product Performance:** Accessories are the most frequently purchased category; "Tires and Tubes" is the top-selling sub-category.
- **Customer Segmentation:** Young adults tend to purchase higher-priced items; seniors prefer more affordable products.
- **Correlations:** Strong positive correlations exist between unit price, unit cost, profit, cost, and revenue. Order quantity is negatively correlated with unit price and unit cost.

---

## How to Use

1. Open the Jupyter Notebook and run each cell sequentially.
2. Review the markdown explanations and visualizations for insights.
3. Use the findings to inform business decisions related to bike sales.

---

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
