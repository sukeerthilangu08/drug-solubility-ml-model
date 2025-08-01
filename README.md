 # LogS Prediction Using Machine Learning Regression Models

This repository contains machine learning models developed to predict the aqueous solubility of chemical compounds, represented as LogS values. The goal is to evaluate and compare different regression algorithms to determine their effectiveness in predicting molecular solubility using a structured set of molecular descriptors.


--------------------------------------------------------------------------------


## Project Overview

This project explores the relationship between molecular features and solubility (LogS) through supervised regression techniques. Two models were trained and evaluated:

- Linear Regression: A baseline linear model to predict LogS.

- Random Forest Regressor: An ensemble tree-based model capable of capturing non-linear relationships.


The comparison was based on performance metrics such as Mean Squared Error (MSE) and R-squared (R²).


--------------------------------------------------------------------------------


## Key Features

- Data Preprocessing: Cleaned and prepared the dataset with relevant features for modeling.

- Model Training: Implemented and trained multiple regression models.

- Performance Evaluation: Measured MSE and R² on training and test datasets.

- Visualization: Created a scatter plot of predicted vs. experimental LogS values with a regression line.


--------------------------------------------------------------------------------


## Models Used

- Linear Regression: Baseline model for interpretable linear relationships.

- Random Forest Regressor: Ensemble method for capturing complex feature interactions.


--------------------------------------------------------------------------------


## Project Structure

drug-solubility-ml-model/

├── first_ML_project.ipynb # Final visualizations

├── requirements.txt # Python dependencies

└── README.md # Project overview



--------------------------------------------------------------------------------


## Dataset

The dataset includes molecular features (descriptors) and corresponding LogS values. It was split into training and test sets to evaluate model generalization.

Note: Dataset is not included in the repository due to licensing or size constraints.


--------------------------------------------------------------------------------


## Results

| Model              | Train MSE | Train R² | Test MSE | Test R² |
|-------------------|-----------|----------|----------|---------|
| Linear Regression | 1.0075    | 0.7645   | 1.0207   | 0.7892  |
| Random Forest     | 1.0282    | 0.7597   | 1.4077   | 0.7092  |

Observation: Linear Regression showed better generalization performance, while Random Forest achieved slightly better results on the training set but exhibited overfitting on the test set.


--------------------------------------------------------------------------------


## Final Visualization

A scatter plot of predicted vs. experimental LogS values was created for the Linear Regression model to visually assess prediction accuracy. A best-fit regression line was added for interpretability.


--------------------------------------------------------------------------------


## How to Run

1. Clone the repository:  
   git clone https://github.com/sukeerthilangu08/drug-solubility-ml-model  
   cd drug-solubility-ml-model

2. Install the required dependencies:  
   pip install -r requirements.txt

3. Run the Jupyter Notebook:  
   jupyter notebook

4. Open and run the notebook:  
   first_ML_project.ipynb


--------------------------------------------------------------------------------


## Conclusion

This project demonstrates that:

- Simple models like Linear Regression can generalize well when the relationship is mostly linear.

- Random Forest offers flexibility but may overfit without proper tuning or data augmentation.

- Visualizations are essential for model validation and understanding prediction behavior.


--------------------------------------------------------------------------------


## Author

Sukeerthi Langu  
GitHub: https://github.com/sukeerthilangu08
