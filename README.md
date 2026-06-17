# PTT Stock Price Forecasting Model & Evaluation 📈
**Advanced Statistical & Quantitative Modeling (Senior Project)**

## 📌 Project Overview
This repository contains a comprehensive quantitative research project focused on predicting PTT stock price movements using historical financial market data. Rather than relying on a single model, this project implements a rigorous **Model Comparison Framework**—evaluating 6 different statistical approaches to optimize prediction accuracy and minimize forecasting errors, which is heavily aligned with quantitative risk and financial forecasting methodologies.

---

## Business & Analytical Objectives
* **Trend Analysis:** Identify underlying patterns, seasonal effects, and cyclical trends in historical equity data.
* **Volatility & Forecasting:** Develop a highly accurate predictive model to assist in data-driven investment strategies and financial risk assessment.
* **Model Optimization:** Benchmark traditional time-series methods against hybrid and structurally optimized alternatives to discover the most robust framework (Champion Model).

---

## Tech Stack & Methodology
* **Tool:** SPSS (Statistical Package for the Social Sciences), R (ggplot2)
* **Techniques:** Time-Series Analysis, Feature Engineering, Optimization, Exogenous Factor Evaluation.

### The 6 Models Evaluated & Compared:
1. **Traditional Models:** * `ARIMA` (AutoRegressive Integrated Moving Average) - Standard univariate time-series.
   * `ARIMAX` - Multivariate approach incorporating external market indicators.
2. **Hybrid Frameworks:**
   * `ARIMA - ARIMAX` - Combining univariate structure with multivariate exogenous inputs.
3. **Optimized (Improved) Frameworks:**
   * `Improved ARIMA` - Structurally adjusted to enhance traditional boundaries.
   * `Improved ARIMAX` - Optimized external variable weightings.
   * `Improved ARIMA - Improved ARIMAX` - The ultimate optimized hybrid ensemble.

---

## 💡 Key Insights & Results

### Model Performance & Trend Visualization
![Forecasting Graph](<img width="1920" height="1080" alt="forecast_graph" src="https://github.com/user-attachments/assets/8046c1b4-f79f-43ab-99c8-2cc62d8c08b5" />)
*Comparison of Actual vs. Predicted PTT Stock Prices across all 6 models.*

### Error Metrics & Evaluation
![Evaluation Table](<img width="1920" height="1080" alt="evaluation_table" src="https://github.com/user-attachments/assets/24734ec5-d01b-49aa-9537-17a89f6bd02d" />)

* **The Winner (Champion Model):** The hybrid **Improved ARIMA - Improved ARIMAX** model emerged as the most efficient and robust framework, achieving the lowest forecasting error with a **MAPE of 1.3854%** and a superior goodness-of-fit with an **R-Squared of 99.5725%**.
* **Significant Exogenous Factors:** The multivariate regression layer identified that PTT's stock price was heavily influenced by the following key factors (ordered by statistical impact):
  1. **Dow Jones Industrial Average (DJIA):** Reflecting global macroeconomic market sentiment.
  2. **PTT Stock Daily High Price:** Capturing immediate intraday momentum.
  3. **PTT Stock Trading Volume:** Indicating market liquidity and investor interest.
* **Conclusion:** The structural enhancements applied to both time-series and regression boundaries in the "Improved Hybrid" version significantly minimized residual errors and provided outstanding forecasting accuracy for highly volatile equity markets.

---

## 🎓 Project Team & My Role
* **Project Type:** Academic Senior Project (Collaborative Group Work)
* **My Role:** Shared equal responsibility across all end-to-end project phases. Actively collaborated with team members to:
  * Process, clean, and prepare historical financial datasets.
  * Build, evaluate, and optimize all 6 time-series forecasting models (including the champion Hybrid model) using SPSS.
  * Analyze error metrics (MAPE, R-Squared) and synthesize actionable financial insights for the final presentation.
* **Author/Team Member:** Tatchaya Puangkaew (B.S. in Statistics, Thammasat University)
* **LinkedIn:** [tatchaya-puangkaew](https://linkedin.com/in/tatchaya-puangkaew-70a680298)
