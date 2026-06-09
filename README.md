# Comparing two Linear Regression Models for Predicting Student Academic Performance

## Project Overview

This project uses Linear Regression to predict students' final grades (G3) using the Student Performance Dataset.

The study compares two predictive models:

### Model 1

Predicts the final grade (G3) using all available features, including previous grades (G1 and G2).

Research Question:
Can we accurately predict a student's final grade if their previous grades are known?

### Model 2

Predicts the final grade (G3) without using previous grades (G1 and G2).

Research Question:
Can demographic, academic, and lifestyle factors predict student performance without prior academic results?

## Dataset

The dataset contains information on 395 secondary school students including:

* Age
* Gender
* Family background
* Parents' education
* Study time
* Absences
* Alcohol consumption
* Internet access
* Academic grades (G1, G2, G3)

Target Variable:

* G3 (Final Grade)

## Machine Learning Workflow

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. One-Hot Encoding of Categorical Features
5. Train-Test Split
6. Linear Regression Training
7. Model Evaluation

## Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## Results

The comparison demonstrates the impact of previous academic performance on final grade prediction accuracy.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

[Your Name]
