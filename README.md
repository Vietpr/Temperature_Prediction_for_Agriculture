# Temperature Prediction for Agriculture Using Machine Learning ☔⛅

## Introduction

The agricultural sector faces significant challenges due to the variability of weather conditions, impacting crop growth, water management, and overall farm planning. To address this challenge, accurate temperature forecasting tailored to agricultural requirements is crucial.

## Objective
This project focuses on developing temperature prediction models using machine learning algorithms to empower farmers in making informed decisions regarding planting timing, crop selection, and resource allocation.

## Data Exploration and Preprocessing
* Data Analysis: Inspected the dataset for shape, null values, data types, and statistical summary.
* Correlation Analysis: Generated a correlation matrix to identify relationships between variables.
* Visualization: Created violin and KDE plots to visualize distributions of key weather features.
* Outlier Detection and Handling: Identified and replaced outliers using the mean of respective columns.
* Normalization: Applied Min-Max Scaling to normalize the data for key weather features.

## Model Training
1. Linear Regression and SVR
* Target Variables: tempmax and tempmin
* Data Splitting: The data was split into training and test sets in an 80/20 ratio.
* Evaluation: The models were evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) on both the training and test sets.
2. XGBoost
* During the training of the XGBoost model, I encountered overfitting issues. To address this, I applied hyperparameter tuning to optimize the model’s performance and reduce overfitting.

## Evaluate and result
#### Results for Tempmax
  ![image](https://github.com/user-attachments/assets/e96b4c2b-3d04-4e0f-9b66-efe9954bbb54)

#### Results for Tempmin
  ![image](https://github.com/user-attachments/assets/d25ab3d3-c6e7-4471-ab5a-7160468034c1)

##  Conclusion
XGBoost consistently outperforms both Linear Regression and SVR in predicting both maximum and minimum temperatures. It has the lowest MSE and RMSE, and the highest R² values in both scenarios, making it the most reliable and accurate model for this temperature prediction task. This demonstrates the effectiveness of XGBoost, especially after addressing overfitting issues through hyperparameter tuning.

## Contact
For any questions or suggestions, please contact Viet at your phamvietofficial@gmail.com

👉 𝐂𝐨𝐩𝐲𝐫𝐢𝐠𝐡𝐭 𝐛𝐞𝐥𝐨𝐧𝐠𝐬 𝐭𝐨 𝐏𝐡𝐚𝐦 𝐕𝐚𝐧 𝐕𝐢𝐞𝐭 👈
