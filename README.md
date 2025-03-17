# House_Price_Prediction

## Introduction
The **House Price Prediction** project focuses on predicting housing prices using machine learning techniques. By leveraging popular Python libraries such as NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, and XGBoost, this project provides an end-to-end solution for accurate price estimation.

This project is particularly useful in the real estate and finance sectors, helping buyers, sellers, and investors make informed decisions based on data-driven insights.

## Key Features
- **Data Collection and Processing**
  - The project utilizes the **California Housing** dataset from Scikit-learn.
  - Features include house age, number of rooms, population, and median income.
  - Pandas is used for data preprocessing and transformation.

- **Data Visualization**
  - Matplotlib and Seaborn are used for visualizing the dataset.
  - Histograms, scatter plots, and correlation matrices help identify trends and patterns.

- **Train-Test Split**
  - The dataset is divided into training and testing subsets.
  - Ensures model evaluation on unseen data for accurate performance assessment.

- **Regression Model using XGBoost**
  - The XGBoost algorithm is employed for regression.
  - Known for handling complex relationships and achieving high predictive accuracy.
  - Scikit-learn provides the implementation of XGBoost used in this project.

- **Model Evaluation**
  - The performance of the regression model is assessed using:
    - **R-squared error**: Measures how well the model explains variance in the target variable.
    - **Mean Absolute Error (MAE)**: Quantifies the average difference between predicted and actual house prices.
  - A scatter plot is created to visualize predicted vs. actual prices.

## Dependencies

Ensure you have the following installed:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost

## Results

- The trained XGBoost model achieves high predictive accuracy.
- The visualization plots provide insights into feature importance and correlations.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

