## 🎯 Final Presentation: Summary and Impact

### 🔍 1. Key Findings

-   There is a clear **positive correlation between temperature** and the total number of bike rentals, especially for **registered users**.
    
-   **Seasonal trends** show increased usage in **summer and spring**, with noticeable drops in **winter**.
    
-   **ARIMA models** (both auto and manual) were successfully fitted to the cleaned time series, and **forecasts for the next 25 days** were generated with reasonable confidence.
    
-   Anomaly detection and smoothing techniques helped in **improving data quality** before modeling.
    

----------

### 🛠 2. Process and Decisions

-   The project began with **exploratory data analysis** to understand variable relationships and temporal patterns.
    
-   Applied **interactive visualizations** using `timetk` to identify seasonal behaviors and anomalies.
    
-   Used **data smoothing** (SMA and exponential methods) to reduce noise and prepare the data for forecasting.
    
-   Evaluated stationarity and used **differencing** where necessary to meet ARIMA model assumptions.
    
-   Compared **manual vs. auto ARIMA** models and selected the one with lower AIC for final forecasting.
    

----------

### 📈 3. Business Value and Impact

-   The forecasts allow **operational teams to plan bike availability** more accurately.
    
-   Knowing the relationship between weather and rentals supports **marketing campaigns** during favorable seasons.
    
-   Helps decision-makers to **optimize fleet management** and staffing based on demand patterns.
    

----------

### ✍️ 4. Communication Style

This report was written with a **clear, professional tone**, avoiding unnecessary jargon. The code is **well-commented**, and all insights are **backed by visualizations or statistical output**.
