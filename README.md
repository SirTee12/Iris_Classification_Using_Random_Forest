# Project Title: Iris Dataset Classification using Random Forest Regressor
## Overview
This project aims to perform classification on the famous Iris dataset using a Random Forest Regressor machine learning model. The goal is to achieve high accuracy in classifying iris flowers into three different species based on their features: sepal length, sepal width, petal length, and petal width.

## Dataset
The Iris dataset used in this project is a well-known dataset available in scikit-learn. It contains 150 samples of iris flowers, each from one of three species: Setosa, Versicolor, and Virginica. The dataset comprises four features (sepal length, sepal width, petal length, and petal width) and their corresponding target labels.

## Project Steps
##Data Cleaning:
+ Checked for missing values: Ensured that there were no missing values in the dataset.
+ Removed duplicates: Checked for and removed any duplicate records in the dataset.
+ Validated data integrity: Examined the dataset for any erroneous or unrealistic values and corrected them as needed.

## Data Visualization:
+ Performed initial data visualization to gain insights into the dataset.
+ Visualized the distribution of the different iris species using histograms, scatter plots, and other relevant plots.
+ Explored the correlations between features using correlation matrices and pair plots.

## Model Selection:
Chose Random Forest Regressor as the classification model for this project due to its effectiveness in handling complex datasets and its ability to provide feature importance scores.
Hyperparameter Tuning:

+ Employed hyperparameter tuning techniques to optimize the performance of the Random Forest Regressor model.
+ Used Randomized Search Cross-Validation (RandomizedSearchCV) to search for the best combination of hyperparameters.

## Model Training and Evaluation:
+ Split the dataset into training and testing sets.
+ Trained the Random Forest Regressor model on the training data.
+ Evaluated the model's performance using various metrics, with a primary focus on accuracy.
+ Achieved a remarkable accuracy of 97.77%.

## Repository Structure
The project repository is organized as follows:

## Data: Contains the Iris dataset used in the project.
Notebooks: Jupyter notebooks used for data cleaning, data visualization, model training, and hyperparameter tuning.
Scripts: Python scripts for specific functions or utility functions used in the project.
Models: Saved trained Random Forest Regressor model(s).
Results: Contains project results, including evaluation metrics and visualizations.
README.md: This README file, providing an overview of the project and its components.
Dependencies

To run this project, you'll need the following Python libraries:

+ NumPy
+ Pandas
+ Matplotlib
+ Seaborn
+ Scikit-Learn
