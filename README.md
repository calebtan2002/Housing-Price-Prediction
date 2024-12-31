# Housing Price Prediction with PySpark

## Overview
This project focuses on predicting house sale prices based on various features, including overall quality, living area, garage area, basement area, and several others. By employing robust data preprocessing and machine learning techniques, I aim to develop predictive models capable of accurately estimating housing prices. The project is implemented in Python, utilizing PySpark for scalable data processing and modeling. Although PySpark might be excessive for this dataset's relatively small size, its inclusion serves as a learning opportunity for me to explore big data frameworks and scalable machine learning workflows.

## Dataset
The dataset contains 1461 rows and 81 columns, with details about individual houses sourced from Kaggle. Among these, 79 features provide information about various aspects of the houses, which collectively influence their sale prices. A comprehensive description of each variable is available in the `data_description.txt` file.

## Data Preprocessing:

- Handling missing values

- Outlier detection and removal

- Encoding categorical features

## Machine Learning Modeling 

- Linear Regression

- Random Forest Regression

Evaluation Metrics used: Root Mean Squared Error (RMSE) and R-Squared (R²).

## Results
### Linear Regression:
Achieved an R² value of 0.90 

### Random Forest Regression:
Achieved an R² value of 0.86, slightly underperforming compared to Linear Regression.


### Model Selection:
Linear Regression was chosen as the final model due to higher performance metrics.

## Future Improvements
- Experiment with additional models like Gradient Boosting such as XGBoost or LightGBM.

- Perform additional hyperparameter tuning for Random Forest.

- Creating new combinations of variables and transforming existing data for better predictive performance
