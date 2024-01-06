# NY Taxi Tip Amount Prediction Project

## Overview
This project aims to predict tip amounts for taxi rides in New York City based on various features using machine learning techniques. The prediction model was built using the Random Forest algorithm.

## Files and Folders
- `NYC taxi tip predictions.ipynb`: Contains the code for the tip amount prediction using Random Forest.
- `NYC taxi trips EDA.ipynb`: Exploratory Data Analysis notebook.
- `README.md`: This file.

## Part 1: Loading Data
- Directly loads data from a URL into a Pandas DataFrame for analysis and modeling.

## Part 2: Data Preprocessing
- Removes observations with missing values.
- Converts columns to appropriate data types.
- Removes invalid or outlier values for specific columns.
- Filters dataset based on trip distances and amounts to refine the dataset.

## Part 3: Feature Selection
- Selects relevant features for model building based on correlation analysis with tip amounts.

## Part 4: Model Building
- Uses Random Forest regression to build a machine learning model for tip amount prediction.

## Part 5: Model Evaluation
- Evaluates model performance using Mean Squared Error (MSE).
- Conducts a hyperparameter tuning analysis using different values for n_estimators.

## Part 6: Feature Importance
- Determines feature importance using the trained Random Forest model.

## Exploratory Data Analysis (EDA) File
- Explores data quality, missing values, types of data, and conducts data preparation, analysis, and visualization.
- Summarizes findings and challenges in using the dataset effectively.

## Conclusion
This project's main goal was to predict tip amounts for taxi rides in NYC using machine learning. It involved extensive data preprocessing, feature selection, model building, and evaluation. Additionally, the EDA file highlights the challenges and limitations of the dataset for deriving meaningful insights.

Note: The EDA file suggests that the dataset may not be ideal due to missing values and poor data quality, impacting the accuracy of predictions.

## Future Improvements
- Seek better data sources with higher quality and less missing data.
- Experiment with different machine learning algorithms for potentially better performance.
