## Cooking Oil Price Prediction

### Overview
- This study explores the application of SARIMA and LSTM models for forecasting cooking oil prices across various Malaysian states, including Kuala Lumpur and Johor. By leveraging historical price data from 2022-2023 provided by the Ministry of Domestic Trade and Consumer Affairs (KPDN) , we aim to provide accurate and reliable forecasts that can aid stakeholders in decision-making processes.
  
### Features
- **Preliminary analysis:** To understand the dataset's structure, format, and types of variables. The `.info()` function provides detailed information about each attribute in the dataset,including datatype, number of rows, and count of null values. 
- **Data Cleaning:** To ensures dataset accuracy and consistency by identifying and handling missing values, and removing unnecessary rows and columns. 
- **Data Concatenation:** To combine multiple similar datasets into a single cohesive dataset, essential when data is collected in batches over time. This process is demonstrated using the PriceCatcher datasets from January 2022 and February 2022 
- **Data Merging:** To integrates the PriceCatcher dataset with the Premise Lookup and Item Lookup datasets. This creates a comprehensive dataset with detailed information about premises and items. 
-**Data Aggregation:**  To group data by 'date' and calculate the mean 'price' for each date 
-**Data Normalization:** To scales data to a specific range, typically between 0 and 1, which helps in accelerating the convergence of the training process and avoiding issues related to different scales of features.
-**Modeling:** Implemented SARIMA and LSTM models for each state for cooking oil price prediction.
- **Evaluation:** Assessed model performance using metrics like MAE, RMSE, MAPE

### Data
- The data is downloaded from the Malaysia Open Data Portal at (https://data.gov.my/data-catalogue)

  
  

![Data Overview](https://github.com/juna-99/Cooking-Oil-Price-Prediction/blob/bf0310482da32a530867a1c4feb16993f9ae2ac6/PowerBI%20img/Screenshot%202024-08-13%20225053.png)
![Cooking Oil Data Overview](https://github.com/juna-99/Cooking-Oil-Price-Prediction/blob/bf0310482da32a530867a1c4feb16993f9ae2ac6/PowerBI%20img/Screenshot%202024-08-13%20225149.png)\
![SARIMA & LSTM](https://github.com/juna-99/Cooking-Oil-Price-Prediction/blob/bf0310482da32a530867a1c4feb16993f9ae2ac6/PowerBI%20img/Screenshot%202024-08-13%20225213.png)
