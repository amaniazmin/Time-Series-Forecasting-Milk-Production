# Time Series Forecasting: Monthly Milk Production Analysis
### Tools Used: Excel, Google Sheets | Methods: Moving Averages, Decomposition Models
Predictive analytics project using Excel/Google Sheets to forecast monthly production trends through Moving Average smoothing and Multiplicative/Additive decomposition models.

## Project Overview
This project performs a time series analysis on historical production data to identify seasonal patterns and forecast future trends. The study compares different statistical smoothing and decomposition techniques to determine the most accurate model for this specific dataset.

## Dataset
The data used in this analysis is the **Monthly Milk Production (Pounds)** dataset (1962–1975), originally sourced from the U.S. Department of Agriculture.
* **Direct Link**: [Monthly Milk Production on Kaggle](https://www.kaggle.com/datasets/pkmisra/monthly-milk-production-pounds)

## Analytical Methodology
The analysis was conducted using a structured predictive modeling workflow:
1. **Data Smoothing**: Implemented **3-Year Moving Averages (MA)** and **Centered Moving Averages (CMA)** to remove short-term noise and isolate the underlying trend.
2. **Decomposition**: Compared the **Additive Method** and the **Multiplicative Method** to account for seasonal variations.
3. **Model Validation**: Calculated the **Mean Squared Error (MSE)** for both models to evaluate forecasting accuracy.

## Key Findings & Performance
Based on the quantitative validation, the models yielded the following results:
* **Multiplicative Method MSE**: 446.11936
* **Additive Method MSE**: 446.14862

**Conclusion**: The **Multiplicative method** was selected as the superior model for this dataset, as the lower MSE indicates that its predictions align more closely with the actual historical values.


