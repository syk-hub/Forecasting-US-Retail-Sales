# Retail Sales Forecasting

## Project Overview

Forecasting retail sales is crucial for businesses, policymakers, and economists alike, as it helps gauge the health of consumer spending—a key driver of the US economy. This study was motivated by the unprecedented disruptions caused by the COVID-19 pandemic, which threw economic forecasts into uncertainty. Retail sales, in particular, faced sharp declines and rapid recoveries, leaving a gap in understanding how resilient long-term economic patterns truly are.

In this project, we applied various time series forecasting models to US monthly retail sales data, focusing on how quickly the economy returned to predicted patterns after such a severe shock. The most surprising finding was the **resilience of the long-term retail sales trends**. Despite the significant disruptions caused by COVID-19, our analysis using the ARIMA model revealed that the economy's underlying structure allowed retail sales to eventually realign with pre-pandemic forecasts. This showcases the robustness of the US retail market, even in the face of temporary disturbances.

Through this analysis, we demonstrate the value of using advanced forecasting methods, such as ARIMA and ETS, to capture complex economic trends. This project not only provides insights into forecasting retail sales but also highlights the power of long-term economic stability.

## Key Models
1. **Seasonal Naive Model (SNaive)**: Provides a simple benchmark for comparison.
2. **ETS Model**: Captures both trend and seasonal components effectively.
3. **ARIMA Model**: The most accurate model in predicting long-term retail sales, particularly post-pandemic.

## Key Results
- The ARIMA model performed the best, demonstrating how retail sales trends returned to predicted values after the COVID-19 disturbances.
- ETS offered a reasonable performance but exhibited some residual autocorrelation.
- The SNaive model served as a useful baseline, but it lacked the sophistication to handle complex patterns in the data.

## Data
The retail sales data is stored in the `data/` directory of this repository as `retail_sales.csv`. The data was sourced from [data source link] and processed for time series analysis.

## Instructions
1. Clone the repository.
2. Install the required R packages: `fpp2`, `ggplot2`, `forecast`.
3. Run the analysis in the R Markdown file `sales_forecasting_analysis_fpp2.Rmd`.

For a detailed breakdown of the analysis, refer to the [R Markdown file](`sales_forecasting_analysis_fpp2.Rmd`), which contains the full code, explanations, and insights into the models used.

## Visualizations
- **Seasonal Plot**: Shows recurring seasonal trends in retail sales.
  ![Seasonal Plot](link-to-image)
  
- **ARIMA Forecast Plot**: Displays the forecasted vs. actual retail sales, highlighting the post-pandemic recovery.
  ![ARIMA Forecast Plot](link-to-image)

- **Residual Diagnostics**: Shows how well the ARIMA model fits the data through residuals analysis.
  ![Residuals Check](link-to-image)

## Conclusion
This project demonstrates the resilience of long-term retail sales trends, even in the face of significant economic disruptions. For more details, please explore the full analysis in the R Markdown file.

