# Global-Mart Customer Analysis

## Overview
End-to-end analysis of e-commerce customer data: cleaning, EDA, prediction, and segmentation.

## Dataset
- Source: Kaggle (Ecommerce Customers)
- 500 records, 8 features (after cleaning: 5 numeric features)

## Workflow
1. Data Acquisition & Inspection (Pandas)
2. Data Cleaning (drop irrelevant cols, duplicates, outliers check)
3. Feature Engineering (StandardScaler)
4. EDA (correlation heatmap, pairplot)
5. Modeling (Linear Regression)
6. Segmentation (K-Means, k=3)
7. Visualization (Matplotlib + Plotly)

## Key Insights
- **Length of Membership** strongly drives spending (r ≈ 0.81)
- **Time on App** moderately impacts spending
- **Time on Website** has weak impact
- 3 segments: **High**, **Medium**, **Low** value customers

## Model Performance
- MAE ≈ 8.5
- Low error relative to average spend (~499) → reliable predictions

## Customer Segments
- High value: long membership, high spend
- Medium value: moderate engagement
- Low value: short membership, low spend

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Plotly

## Project Structure
