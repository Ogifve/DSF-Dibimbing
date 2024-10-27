# DSF-Dibimbing
# Titanic Survival Prediction

This repository contains the code and resources for a data science project aimed at predicting passenger survival on the Titanic. This project was created as part of a bootcamp learning module focused on exploratory data analysis (EDA), data preprocessing, and machine learning model building.

## Project Overview

The Titanic Survival Prediction project uses data from the [Titanic dataset](https://www.kaggle.com/c/titanic) to develop a model that predicts which passengers are likely to survive. This classic dataset provides insights into various passenger characteristics, including age, gender, class, and more, and is commonly used to practice machine learning classification tasks.

## Objectives

- Conduct data cleaning and preprocessing, including handling missing values, feature engineering, and encoding categorical variables.
- Perform exploratory data analysis (EDA) to uncover patterns and insights about passenger survival.
- Build, train, and evaluate different machine learning models to predict survival.
- Compare model performance and optimize the chosen model for accuracy.

## Dataset

The dataset contains data on Titanic passengers and includes the following columns:

- `PassengerId`: Unique ID for each passenger
- `Pclass`: Passenger class (1st, 2nd, or 3rd)
- `Name`: Passenger's name
- `Sex`: Passenger's gender
- `Age`: Passenger's age
- `SibSp`: Number of siblings or spouses aboard
- `Parch`: Number of parents or children aboard
- `Ticket`: Ticket number
- `Fare`: Ticket fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
- `Survived`: Survival status (0 = No; 1 = Yes)

## Project Workflow

1. **Data Preprocessing**: 
    - Handling missing values for `Age`, `Cabin`, and `Embarked`.
    - Encoding categorical variables like `Sex` and `Embarked`.
    - Feature engineering to create new variables from existing data.

2. **Exploratory Data Analysis (EDA)**:
    - Visualizing survival rates across different groups (e.g., by gender, class).
    - Analyzing the impact of features such as `Age` and `Fare` on survival.

3. **Model Building**:
    - Trying various machine learning algorithms including Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, and Random Forest.
    - Splitting the data into train and test sets for model evaluation.
    - Using cross-validation to fine-tune and select the best model.

4. **Model Evaluation**:
    - Assessing model performance using accuracy, precision, recall, and F1-score.
    - Selecting the most accurate model based on these metrics.

## Results

The project achieves a prediction accuracy of approximately **XX%** using the best-performing model, Random Forest. The results demonstrate that certain features, such as `Sex`, `Pclass`, and `Fare`, play a significant role in determining passenger survival.

## Getting Started

To run this project on your local machine:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/titanic-survival-prediction.git
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook to view the analysis and model predictions.

## Project Structure

- `data/`: Contains the dataset.
- `notebooks/`: Jupyter Notebook files with EDA and model building.
- `src/`: Python scripts for data preprocessing, model training, and evaluation.
- `README.md`: Project documentation.

## Conclusion

The Titanic Survival Prediction project provides hands-on experience with data preprocessing, feature engineering, and machine learning. By working on this project, we gain insights into the process of building a predictive model, from data cleaning to model optimization.

---

Thank you for exploring this project! If you have any questions or suggestions, feel free to open an issue or submit a pull request.
