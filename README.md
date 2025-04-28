# health_insurance
 Case study using linear regression


## Health Insurance Cost Prediction ##

### Project Overview ###
This project focuses on predicting individual health insurance charges based on personal attributes.
Using a real-world dataset, we built and evaluated machine learning models to estimate costs accurately and identify key factors influencing pricing.

### Main Steps ###
Exploratory Data Analysis (EDA):
Analyzed data distributions, relationships, and correlations to understand the main drivers behind insurance charges.

- Data Preprocessing:

Handled categorical variables through encoding

Dropped less informative features (e.g., region) after correlation analysis

- Modeling:

Trained and evaluated Linear Regression and Decision Tree Regression models

Applied Cross-Validation to ensure robust performance evaluation

- Model Selection:

Based on cross-validation results, Linear Regression was selected as the final model, achieving an R² score of 0.78.

### Key Findings ###
- Age, BMI, and Smoking Status have the strongest influence on insurance charges.

- Smokers are significantly more expensive to insure, showing much higher charges on average.

- Variables like Region had little correlation with insurance costs and were removed to simplify the model.

### Final Model Performance ###

- Model	R² Score (Cross-Validation) - Linear Regression	0.78
  
- Decision Tree Regression - Lower than Linear Regression (not selected)


### How to Run the Project ###
Clone the repository.

Install the required libraries:

bash
Copiar
Editar
pip install pandas numpy matplotlib seaborn scikit-learn
Open the Jupyter Notebook health_insurance.ipynb.

Run the notebook to follow the analysis step-by-step.

### Technologies Used###
Python 3

Pandas

Numpy

Seaborn

Matplotlib

Scikit-Learn

