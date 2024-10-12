Project Overview
This project focuses on forecasting US monthly retail sales (inflation-adjusted) from 1992 to 2024 using advanced time series forecasting models. The analysis examines long-term economic trends and highlights the surprising resilience of the US economy, especially after disruptions like the COVID-19 pandemic. The final forecast shows how the economy returns to predicted patterns after temporary shocks.

Methodology
The study involves several key steps:

Pre-processing the Data: Transform the data into a time series object for analysis.
Exploring Trends and Seasonality: Initial visualizations help identify patterns such as seasonality and trends over time.
Modeling Techniques: Three forecasting models are tested:
Seasonal Naive (SNaive)
Exponential Smoothing (ETS)
ARIMA
Model Evaluation: The models are compared based on error metrics like RMSE and MAE, and residual analysis is conducted.
Forecasting: Using the best-performing model (ARIMA), future retail sales are forecasted. Special attention is given to the impact of COVID-19 and the eventual recovery of the economy.
Key Results
The analysis shows that:

ARIMA is the most accurate model, with the lowest RMSE and residual autocorrelation, making it ideal for forecasting long-term retail sales.
ETS performs reasonably well but shows some residual autocorrelation.
The SNaive model serves as a useful baseline but is not sophisticated enough to handle the complexities of retail sales data.
Post-COVID-19, the economy returned to pre-pandemic patterns, with the ARIMA model's forecast closely aligning with the actual data as the disturbances subsided.

Data Source
The retail sales data used in this analysis is sourced from [include your data source here], and was processed as a time series object for the analysis.

Instructions
To reproduce this analysis:

Clone this repository.
Run the R Markdown file sales_forecasting_analysis_fpp2.Rmd.
Ensure that all necessary packages, such as fpp2, are installed.
Required Packages
fpp2: For time series forecasting models.
ggplot2: For data visualization.
forecast: For working with ARIMA models.
Visualizations
You can include key visualizations from the analysis, such as:

Seasonal Plot: A visualization showing seasonal patterns in retail sales.
ARIMA Forecast Plot: Displays the forecasted vs. actual values, particularly focusing on the COVID-19 recovery period.
Residual Diagnostics: Graphs for each model showing the residual patterns and assessing model fit.
Conclusion
This study underscores the resilience of long-term economic structures, even after major disruptions like COVID-19. The ARIMA model captures this recovery well, making it a reliable tool for retail sales forecasting.

