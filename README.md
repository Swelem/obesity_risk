

# Obesity Prediction Project

This project aims to predict obesity levels based on various features such as gender, age, height, weight, lifestyle habits, and more. The prediction is made using machine learning techniques on a dataset obtained from a Kaggle competition.

## Dataset

The dataset consists of two main files: `train.csv` and `test.csv`. The training data contains 20758 samples with 18 features, including the target variable 'NObeyesdad' representing different levels of obesity. The test data contains 13840 samples with 17 features.

## Data Acquisition

The dataset was obtained from Kaggle using the Kaggle API. After downloading and unzipping the dataset, it was loaded into pandas DataFrames for further processing.

## Data Exploration

- Checked the shape of the training and test datasets.
- Examined for missing values (none found).
- Explored the distribution of the target variable classes.
- Analyzed the data types of columns.

## Data Preprocessing

- Encoded categorical variables using LabelEncoder.
- Encoded the target variable.
- Scaled numerical features using StandardScaler.

## Data Visualization

- Plotted bar graphs to visualize the distribution of obesity classes.
- Created count plots for each categorical variable to understand their frequency.

## Model Training

### Round 1

- Selected RandomForest, GradientBoosting, and XGBoost classifiers.
- Split the dataset into training and testing sets.
- Trained models and evaluated their performance.
- Selected GradientBoostingClassifier as the best model.

### Round 2

- Evaluated models using cross-validation.
- Selected XGBoostClassifier based on mean accuracy.

### Round 3

- Fine-tuned parameters for XGBoost, RandomForest, and GradientBoost classifiers.
- Selected the best model based on accuracy.

## Submission

- Made predictions on the test data using the best model.
- Prepared the submission file in CSV format.

## Conclusion

This README provides an overview of the obesity prediction project, including data acquisition, exploration, preprocessing, model training, and submission processes. The final model achieved an accuracy of X% on the test data.

