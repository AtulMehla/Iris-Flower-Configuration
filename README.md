# Iris Flower Classification

This project aims to classify Iris flowers into three species based on sepal and petal measurements using multiple classifiers.

## Dataset
The dataset contains 150 samples of Iris flowers, with four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

The target variable is the species of the Iris flower:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Steps
1. Data Preprocessing: Handle missing values and encode categorical variables.
2. Exploratory Data Analysis (EDA): Visualize relationships and correlations.
3. Model Selection: Train and evaluate multiple classifiers (Logistic Regression, Decision Tree, Random Forest, SVM, KNN).
4. Model Evaluation: Evaluate models using accuracy, classification report, and confusion matrix.
5. Feature Importance: Identify the most significant features using Random Forest.

## Results
- Best Model: Random Forest (for its high accuracy and interpretability).
- Alternative: SVM (if you prefer a model that handles complex boundaries well).
- Most Significant Features: Petal length and width

## Requirements
- Python 3.x
- Libraries: pandas, seaborn, matplotlib, scikit-learn
