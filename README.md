## Obesity Prediction Project

This project predicts obesity levels using machine learning techniques on a dataset sourced from a Kaggle competition. It encompasses data exploration, preprocessing, model training, and submission processes.

### Dataset

The dataset comprises `train.csv` and `test.csv`, containing samples with features like gender, age, weight, and lifestyle habits. The target variable 'NObeyesdad' represents different obesity levels.

### Data Exploration

Explored dataset shape, missing values, and target variable distribution. Analyzed data types and visualized obesity class distribution and categorical variable frequencies.

### Data Preprocessing

Encoded categorical variables and scaled numerical features for model compatibility.

### Model Training

- **Round 1**: Trained RandomForest, GradientBoosting, and XGBoost classifiers. Selected GradientBoostingClassifier.
- **Round 2**: Evaluated models using cross-validation. Chose XGBoostClassifier.
- **Round 3**: Fine-tuned XGBoost, RandomForest, and GradientBoost classifiers. Selected best model based on accuracy.

### Submission

Made predictions on test data using the best model and prepared submission file in CSV format.

### Conclusion

This README offers an overview of the obesity prediction project, highlighting data acquisition, exploration, preprocessing, model training, and submission. The final model achieved an accuracy of 0.91437 on the test data. This project serves as an entry for the Kaggle competition [here](https://www.kaggle.com/competitions/playground-series-s4e2).
