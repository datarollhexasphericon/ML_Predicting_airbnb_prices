# Predicting Airbnb Prices

## 1. Project Motivation and Description
This project aims to develop a predictive model for Airbnb listing prices based on various property and location features. Accurate price prediction can help hosts set competitive prices and assist customers in making informed booking choices.

## 2. Data
This project uses **a real-word dataset** sourced from Airbnb property listings via web scraping. 

## 3. Key Components

### 3.1. Data Preparation and Exploration
This project includes an extensive and thorough EDA and feature engineering. `KNNImputer` is applied to handle missing data

### 3.2. Feature Selection
An embedded feature selection is used, i.e. a Random Forest Regression.

### 3.3. Model Definition
Two models are selected for this task and compared: **Random Forest Regressor** and **XGBoost Regressor** due to their robustness and ability to handle complex, non-linear relationships. 

### 3.4. Training and Hyperparameter Tuning
A `GridSearchCV` is employed to identify the optimal hyperparameters for the models. 

## 4. Conclusion
Predicting property prices based on real-world data is a complex and challenging task, but this project achieved significant progress. With a coefficient of determination (R²) of 0.67 on the test set using both Random Forest and XGBoost, the model demonstrates solid predictive power. The minimal discrepancy between training and test performance—a few hundredths for XGBoost and tenths for Random Forest—highlights the model’s robustness and strong generalizability to new data. Future work could focus on advanced feature engineering techniques, such as natural language processing (NLP) to extract valuable insights from text data, potentially pushing predictive accuracy even further.Predicing property prices using real world data is a very complex problem, and although the model's performance is not yet ideal, achieving a coefficient of determination (R²) of 0.67 on the test set with both Random Forest and XGBoost, the performance on the training set shows minimal difference—just a few hundredths for XGBoost and a few tenths for Random Forest. This indicates no overfitting and demonstrates strong generalizability to unseen data. A potential next step would be to dive deeper into feature engineering, for instance, by utilizing NLP modeling to extract insights from the text data.
