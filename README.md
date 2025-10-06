# Tesla Stock Price Forecasting with Prophet

This project explores **Tesla’s stock price behavior** using **Facebook Prophet**, a powerful time series forecasting model. By analyzing historical price data, the model uncovers hidden patterns, detects trend shifts, and predicts future stock movements with visual clarity.

---

##  Project Overview
The goal is to apply data-driven forecasting to gain insights into **Tesla’s market dynamics** and future trajectory. Prophet was chosen for its ability to model non-linear trends with seasonality and holiday effects.

### 🔍 Key Insights
- **Upward Momentum:** The model detects strong long-term growth trends, reflecting Tesla’s sustained market confidence.
- **Volatility Patterns:** Weekly and yearly components show recurring cycles that may correspond to market trading behavior and investor reactions to earnings.
- **Forecast Confidence:** Prophet’s uncertainty intervals highlight periods where forecasts are less stable — useful for assessing investment risks.

---

##  Methodology
1. **Data Preparation**
   - Cleaned and structured Tesla’s historical data (`Tesla.csv`).
   - Renamed columns to Prophet’s expected format (`ds`, `y`).

2. **Exploratory Data Analysis (EDA)**
   - Visualized Tesla’s historical stock movements.
   - Identified rapid growth phases and volatility clusters.

3. **Forecasting with Prophet**
   - Trained a Prophet model on the closing price.
   - Generated future forecasts with trend and seasonality decomposition.

4. **Evaluation & Visualization**
   - Visualized forecasted vs. actual values.
   - Interpreted trend, weekly, and yearly components for insights.

---

##  Tools & Technologies
- **Python**
- **Facebook Prophet**
- **Pandas, NumPy**
- **Matplotlib, Plotly**
- **Jupyter Notebook**
