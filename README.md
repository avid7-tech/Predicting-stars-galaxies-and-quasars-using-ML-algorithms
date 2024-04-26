# Predicting-stars-galaxies-and-quasars-using-ML-algorithms
This repository contains code for classifying galaxies into three classes: Galaxy, Quasar, and Star, using machine learning techniques. The dataset used in this project is the Sloan Digital Sky Survey (SDSS) dataset.

## Dataset
The dataset used in this project is obtained from the Sloan Digital Sky Survey (SDSS). It contains various attributes such as u, g, r, i magnitudes, and class labels representing the type of astronomical object.

## Code Structure
Importing Libraries: The necessary libraries for data handling, visualization, model building, and performance evaluation are imported.
Loading Data: The dataset is loaded into a Pandas DataFrame.
Data Preprocessing:
Object ID columns are dropped as they are not useful for analysis.
Label encoding is applied to convert the class labels into numerical format.
Features are standardized using StandardScaler.
Model Building:
Three classifiers are trained on the preprocessed data: Decision Tree Classifier, Logistic Regression, and K-Nearest Neighbors Classifier.
Model Evaluation:
The models are evaluated using classification reports which include precision, recall, and F1-score for each class, along with overall accuracy.

## Usage
Ensure Python and necessary libraries are installed.
Clone the repository.
Run the provided Python script in a Python environment.
View the classification reports to evaluate the performance of each model.

## Results
The performance of each model is as follows:

Decision Tree Classifier: Precision - 0.99, Recall - 0.99, F1-score - 0.99, Accuracy - 0.99
Logistic Regression: Precision - 0.97, Recall - 0.97, F1-score - 0.97, Accuracy - 0.98
K-Nearest Neighbors Classifier: Precision - 0.90, Recall - 0.93, F1-score - 0.91, Accuracy - 0.91

## Conclusion
The Decision Tree Classifier performs the best among the three models in terms of accuracy and F1-score. Further optimization and tuning of models could potentially improve performance.
