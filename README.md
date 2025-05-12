# Causal Relationships Between Black and Hispanic Unemployment Rates

This project investigates whether there is a **causal relationship** between unemployment rates among **Black (African American)** and **Hispanic or Latino** populations in the United States using time series analysis and **Granger Causality Tests**.

The analysis includes data visualization, stationarity checks, differencing for stability, optimal lag selection using the **Akaike Information Criterion (AIC)**, and final causality testing using a **Vector Autoregression (VAR)** model.

---

## Repository Contents

| File Name                              | Description                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------|
| `african_hispanic_unemployment_analysis.ipynb` | Jupyter notebook with complete workflow: visualization, ADF test, VAR model, and Granger causality tests |
| `civilian unemployment.xlsx`           | Excel file containing monthly unemployment data for Black and Hispanic populations |

---

## 🔍 Key Steps in the Analysis

1. * Visualization**  
   Plots the time series for both populations to observe trends, patterns, or anomalies over time.

2. * Stationarity Check**  
   Uses the Augmented Dickey-Fuller (ADF) test to determine if the time series is stationary—a prerequisite for VAR modeling.

3. * Differencing and VAR Model**  
   Applies first-order differencing to stabilize the data and fits a VAR model, selecting the best lag using AIC.

4. * Granger Causality Test**  
   Tests whether changes in unemployment in one group can statistically predict changes in the other, assessing potential causal links.

---

## Data Source

The unemployment data used in this analysis is sourced from the **U.S. Bureau of Labor Statistics (BLS)**. The dataset includes monthly unemployment figures for:

- **Black or African American**
- **Hispanic or Latino**

The data was extracted and saved as `civilian unemployment.xlsx` for the purpose of this time series and causality analysis.

---

## Requirements

To run the notebook, make sure the following Python libraries are installed:

```bash
pip install pandas matplotlib numpy statsmodels openpyxl
```

---

## Note

This repository is meant for educational and analytical purposes. The Granger causality test does not imply true causality but rather a predictive relationship in time series data.

---

## Contact

For questions or collaboration ideas, feel free to reach out via GitHub or email.
