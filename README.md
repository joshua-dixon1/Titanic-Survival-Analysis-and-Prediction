# Titanic Survival Analysis and Prediction
This repository hosts my machine learning project for the Kaggle Titanic competition, where I analyze and predict survival outcomes using passenger data. The focus is on in-depth exploration, feature engineering, and model optimisation.

## Project Overview
The project tackles the binary classification problem presented by the Titanic dataset: predicting survival based on attributes such as age, sex, and ticket class. I utilised data visualisation, preprocessing, feature engineering, and the deployment of machine learning models, with a particular emphasis on the CatBoost algorithm.

## Data Source
The dataset originates from Kaggle's [Titanic dataset](https://www.kaggle.com/c/titanic/data), containing detailed passenger information and survival indicators.

## Repository Contents
- `titanic_analysis.ipynb`: Analytical Jupyter Notebook.
- `train.csv` & `test.csv`: Training and test datasets.
- `gender_submission.csv`: Example submission format from Kaggle.
- `catboost_submission.csv`: My official competition submission.
- `requirements.txt`: Lists Python package dependencies.
- `README.md`: Documentation and project summary.
- `LICENSE`: The full text of the MIT license.

## Methodology
Key stages of the project include:
1. **Data Exploration**: Delve into feature distributions and interrelationships.
2. **Data Preprocessing and Cleaning**: Address missing values and prepare categorical variables.
3. **Feature Engineering**: Devise new features for enhanced model predictions.
4. **Model Selection and Training**: Evaluate different machine learning algorithms.
5. **Model Tuning and Validation**: Fine-tune the best-performing models and validate their effectiveness.

## Key Achievements
- Validation accuracy of 86.05% with CatBoost.
- A public score of 0.70574 on Kaggle's leaderboard.
- Assessment of various algorithms, with CatBoost being the most accurate.
- Competent performance from Gradient Boosting Trees and Linear SVC, amongst others.

## Technologies Used
- Python
- Pandas and NumPy for data management
- Matplotlib and Seaborn for visualisation
- Scikit-learn for machine learning

## Models Explored
- Main focus on CatBoost for its high accuracy.
- Other models tested include Gradient Boosting Trees, Linear SVC, and Logistic Regression.
- Additional evaluations on Random Forest, Stochastic Gradient Descent, Decision Tree, and Naive Bayes.

## Running the Project
Clone the repository, install dependencies listed in `requirements.txt`, and execute `titanic_analysis.ipynb` in a Jupyter Notebook.

## Contributions
Your contributions, issues, and feature requests are welcomed and appreciated. Please fork the repo, submit a pull request, or open an issue!

## Author
- Joshua Dixon

## License
This project is open-source under the MIT License.
