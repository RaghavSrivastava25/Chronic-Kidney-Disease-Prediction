# Chronic-Kidney-Disease-Prediction

# Chronic Kidney Disease Prediction

This repository contains the code and resources for predicting chronic kidney disease using machine learning techniques. The project includes exploratory data analysis, feature engineering, model selection, hyperparameter tuning, evaluation metrics, visualization, and model persistence.

## Dataset

The dataset used in this project is sourced from the UCL ML repository and focuses on chronic kidney disease. It contains various features related to patients' health conditions and lab test results. The dataset provides the necessary information for training and evaluating the predictive models.

## Project Overview

1. **Exploratory Data Analysis (EDA):** Perform initial data exploration to understand the dataset's structure, identify any missing values, outliers, or data quality issues.

2. **Feature Engineering:** Apply preprocessing techniques such as one-hot encoding to handle categorical variables and other feature engineering techniques to prepare the data for training the machine learning models.

3. **Model Selection:** Choose the Random Forest Classifier as the final model due to its ability to handle complex datasets effectively.

4. **Hyperparameter Tuning:** Optimize the Random Forest Classifier by tuning its hyperparameters to improve its performance on the given dataset.

5. **Evaluation Metrics:** Print accuracy, F1 score, precision, and recall to assess the performance of the trained model.

6. **ROC-AUC Curves:** Plot ROC-AUC curves to visualize the trade-off between true positive rate and false positive rate at different classification thresholds.

7. **Model Persistence:** Save the trained Random Forest Classifier as a pickle file for future use, enabling easy deployment and reuse.

8. **Correlation Heatmap:** Plot a correlation heatmap to visualize the relationships between different features in the dataset, providing insights into potential dependencies.

## Usage

1. Clone the repository:

git clone https://github.com/yRaghavSrivastava25/chronic-kidney-disease-prediction.git


2. Download the dataset:

https://github.com/RaghavSrivastava25/Chronic-Kidney-Disease-Prediction/blob/main/chronic%2Bkidney%2Bdisease.zip


3. Run the main script:

https://github.com/RaghavSrivastava25/Chronic-Kidney-Disease-Prediction/blob/main/Kidney_Disease_Prediction.ipynb

This will execute the entire thing, including data preprocessing, model training, evaluation, and visualization.

4. Explore the results:

- The accuracy, F1 score, precision, and recall metrics will be printed in the console.
- The ROC-AUC curves will be saved as image files for further analysis.
- The trained Random Forest Classifier will be saved as a pickle file for future use.

## Contributing

Contributions to this project are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.


