# Predicting-King-County-Mobility-Trends-with-Forecasting-Models

**Overview:**
This GitHub repository delves into forecasting mobility patterns in King County using historical Google data (2020-2022). The project focuses on residential, work, and grocery/pharmacy mobility trends.

**Why Forecasting Matters:**
Forecasting allows us to predict future trends based on past data. This helps with informed decision-making across various sectors.

**Project Techniques:**
The project utilizes two key forecasting techniques:

1. **Exponential Smoothing (ES):** A powerful method for short-term forecasts.
2. **Autoregressive Integrated Moving Average (ARIMA):**  A flexible approach for handling complex time series patterns.

**Project Steps:**

1. **Data Preparation:**
    - Combine all King County data (2020-2022) into a single DataFrame.
    - Exclude pre-pandemic data (before April 2020) for better trend analysis.
2. **Time Series Analysis:**
    - Decompose each mobility time series (residential, work, grocery/pharmacy) into trend, seasonality, and remainder components. 
3. **Forecasting Models:**
    - Build and evaluate multiple ES models for each time series. Choose the best-performing model based on metrics like MAE and RMSE.
    - Develop ARIMA models for each time series, justifying parameter selection.
4. **Model Comparison:**
    - Compare the best ES and ARIMA models for each time series to identify the most effective model for future predictions.
5. **Future Forecasting:**
    - Utilize the winning models to forecast mobility trends for the remainder of 2022. Visualize past and predicted data for clear comparison.  

**Technical Stack:**

* Python
* Libraries: NumPy, Pandas, Matplotlib, Statsmodels, Scikit-learn, Sklearn

**Invitation to Explore:**

The code repository offers a detailed look at the implementation and results. Feel free to explore for further insights.
-  The code provides a comprehensive view of the process.
-  If you encounter issues or have questions, please consult the documentation or contact the repository owner.
