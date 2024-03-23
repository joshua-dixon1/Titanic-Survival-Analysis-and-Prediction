# Titanic Survival Analysis and Prediction
This repository contains a comprehensive machine learning project that analyses and predicts passenger survival on the RMS Titanic. It represents my submission to the Kaggle Titanic competition, utilising passenger data to predict survival outcomes with a focus on delivering a thorough exploration, feature engineering, and model optimisation.

## Project Overview
The Titanic dataset presents a classic binary classification problem—predicting survival or demise based on variables like age, sex, ticket class, among others. I approached this problem with a systematic analysis pipeline that included data visualisation, preprocessing, feature engineering, and the deployment of various machine learning models, with a primary focus on the CatBoost algorithm as this proved to be the most accurate.

## Data Source
The dataset used in this project is sourced from the [Titanic dataset on Kaggle](https://www.kaggle.com/c/titanic/data). It includes various features such as passenger names, ages, classes, and survival status.

## Repository Contents
- `titanic_analysis.ipynb`: Jupyter Notebook with the exploratory data analysis, data preprocessing, and modeling.
- `train.csv`: Training dataset provided by Kaggle.
- `test.csv`: Test dataset provided by Kaggle.
- `gender_submission.csv`: Kaggle's example submission file for understanding the required format.
- `catboost_submission.csv`: My submission with 86.05% accuracy.
- `requirements.txt` Outlines Python packahes and versions.
- `README.md`: This file, providing an overview of the project.
- `LICENCE`: MIT Licence

## Methodology
The project follows these main steps:
1. **Data Exploration**: Understanding the dataset's features and distributions.
2. **Data Preprocessing and Cleaning**: Handling missing values and categorical data.
3. **Feature Engineering**: Creating new features to better capture the predictive power of the data.
4. **Model Selection and Training**: Implementing various machine learning algorithms to predict survival.
5. **Model Tuning and Validation**: Assessing the performance of models and fine-tuning their parameters.

## Key Achievements
- Achieved an accuracy of 86.05% with the CatBoost Algorithm during validation.
- Attained a public score of 0.70574 on the Kaggle leaderboard upon submission.
- Evaluated various algorithms, with CatBoost showing the highest accuracy.
- Other notable models include Gradient Boosting Trees and Linear SVC with competitive accuracies.

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn for data visualization
- Scikit-learn for machine learning

## Models Explored:
- Explored various algorithms with CatBoost achieving the top accuracy.
- Other models included Gradient Boosting Trees, Linear SVC, Logistic Regression, Random Forest,
  Stochastic Gradient Descent, Decision Tree, and Naive Bayes as a lower baseline.

## How to Run the Project
To run the project, clone the repository, install the necessary Python packages from 
requirements.txt, and launch titanic_analysis.ipynb in a Jupyter environment.

## Contributions
Contributions, issues, and feature requests are welcome. Feel free to fork the repository, 
open a pull request, or submit any issues!

## Author
- Joshua Dixon

## License
This project is licensed under the MIT License.
