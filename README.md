# Optimizing Taxi Demand Predictions for NYC

## 1. About the Dataset
This project focuses on improving taxi service efficiency in New York City (NYC) by predicting taxi demand. The dataset includes historical taxi ride data, which is used to analyze and forecast demand across different areas of the city. The aim is to optimize taxi coverage and enhance service quality.

## 2. Objective
The primary objectives of this project are to:
- Improve taxi service efficiency in NYC by accurately forecasting taxi demand.
- Cluster the city into segments to optimize taxi coverage and service distribution.
- Enhance decision-making for taxi dispatch and resource allocation.

## 3. Approach
The project utilizes the following approach:
- **Data Handling:** Employed the Dask framework to efficiently manage and process large datasets.
- **Distribution Assessment:** Analyzed data distributions using Probability Density Functions (PDFs), log-PDFs, and Q-Q plots.
- **Clustering:** Segmented NYC into clusters using the K-means++ method and visualized these clusters using the Folium library.
- **Time Binning:** Implemented time binning to manage and analyze time-series data effectively.
- **Forecasting Models:** Applied various models for demand forecasting, including:
  - Moving Average (MA)
  - Weighted Moving Average (WMA)
  - Exponential Weighted Moving Average (EWMA)
  - Predictive models such as Linear Regression and Random Forest
- **Feature Engineering:** Conducted feature engineering to improve model performance.

## 4. Results & Key Features
- **Performance Metrics:** Evaluated the models using Mean Absolute Percentage Error (MAPE) and Mean Squared Error (MSE).
- **Accuracy:** Achieved a MAPE of 0.093 using Random Forest Ensembling, demonstrating high accuracy in demand forecasting.

## 5. License
This project is licensed under the MIT License. For detailed licensing information, refer to the [LICENSE](LICENSE) file in this repository.

## 6. Contact
For any questions or feedback regarding this project, please contact:

- **Vivek Radadiya**
