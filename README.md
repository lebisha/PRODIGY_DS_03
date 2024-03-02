# Task-03

## Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.


This project aims to analyze a dataset related to a bank's marketing campaign. The dataset contains various features such as age, job, marital status, education, housing loan status, personal loan status, etc. The target variable is whether the individual subscribed to a term deposit or not.

## Tools and Libraries Used
- Pandas: For data manipulation and analysis.
- Seaborn: For data visualization.
- Matplotlib: For additional data visualization.
- Scikit-learn: For building and evaluating machine learning models.

## Dataset Overview
- **Shape**: The dataset consists of X rows and Y columns.
- **Information**: It provides information regarding the data types and missing values.
- **Statistical Analysis**: Descriptive statistics are used to summarize the central tendency, dispersion, and shape of the dataset's distribution.
- **Missing Values and Duplicates**: Checks for missing values and duplicates in the dataset.

## Data Visualization
- **Age Distribution and Deposits**: Visualizes the distribution of ages among individuals, categorized based on whether they made a deposit or not.
- **Occupation Distribution and Deposits**: Displays the distribution of individuals across different occupations, further categorized by deposit status.
- **Marital Status and Deposits**: Illustrates the distribution of individuals based on their marital status, with further categorization by deposit status.
- **Education Status and Deposits**: Shows the distribution of individuals across different education levels, categorized by deposit status.
- **Housing Loan Distribution and Deposits**: Represents the distribution of individuals based on their housing loan status, with further categorization by deposit status.
- **Personal Loan Distribution and Deposits**: Visualizes the distribution of individuals based on their personal loan status, categorized by deposit status.
- **Pie chart for Outcome**: Presents the proportion of individuals who made deposits versus those who did not using a pie chart.

## Correlation Matrix
- Displays a heatmap of the correlation matrix to visualize the relationships between different numerical variables in the dataset.

## Data Preprocessing
- Label Encoding: Encodes categorical variables into numerical format.
- Train-Test Split: Splits the dataset into training and testing sets.
- Standardization: Standardizes numerical features to have a mean of 0 and a standard deviation of 1.

## Model Training and Evaluation
- Decision Tree Classifier: Trains a decision tree classifier model and evaluates its performance using accuracy score, cross-validation score, and classification report.
- Hyperparameter Tuning: Uses grid search cross-validation to find the best hyperparameters for the decision tree classifier.
- Model Evaluation with Best Estimator: Evaluates the decision tree classifier model with the best hyperparameters using accuracy score and classification report.

## Confusion Matrix
- Displays a heatmap of the confusion matrix to evaluate the performance of the decision tree classifier model.

## Decision Tree Visualization
- Generates a visual representation of the decision tree classifier model.

## Conclusion
The project concludes with insights drawn from the analysis and model evaluation.
