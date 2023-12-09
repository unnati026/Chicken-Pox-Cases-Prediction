# Hungary Chickenpox Time Series Forecasting

This repository contains the code for time series forecasting of chickenpox cases in Hungary using two different models: Prophet and XGBoost. The dataset includes both spatial and temporal information, allowing for a comprehensive analysis of the spread of chickenpox across different counties.

## Overview

- **Spatial Analysis:** The repository starts with a spatial analysis section where the adjacency matrix is created based on the geographical boundaries of Hungarian counties. The matrix is visualized to show connections between counties.

- **Temporal Analysis:** The temporal dataset is explored, and correlations between chickenpox cases in different counties are examined. Line plots are generated to visualize the trend of cases in each county over time.

- **Training Models:** Two models are used for time series forecasting:
  - **Prophet:** The Facebook Prophet library is utilized for forecasting chickenpox cases. Training and test sets are used to evaluate the model's performance.
  - **XGBoost:** XGBoost is implemented both conventionally and with a sliding window approach. The results of training and testing are visualized for each county.

## Files

- `hungary_county_edges.csv`: Dataset containing information about county boundaries.
- `hungary_chickenpox.csv`: Temporal dataset with chickenpox cases for each county over time.
- `hungary.jpg`: Image file displaying the map of Hungary.
- `time-series`: Jupyter Notebook consisting of the code with the above mentioned functions.
- `README.md`: This ReadMe file.