Iris Classification with K-Nearest Neighbors (KNN)
Task Overview
This repository contains the solution for Task 6 of the Elevate AI & ML Internship. The objective is to implement a K-Nearest Neighbors (KNN) classifier on the Iris Dataset to predict Species (Setosa, Versicolor, Virginica).
Steps Performed

Data Preprocessing:
Loaded Iris.csv, dropped Id column, and normalized numerical features.
Encoded Species as numerical labels (0: Setosa, 1: Versicolor, 2: Virginica).
Saved cleaned dataset as Iris_Cleaned.csv.


Exploratory Data Analysis:
Generated summary statistics and class distribution plot.
Created a pairplot to visualize feature relationships.


KNN Classifier:
Trained KNN with different K values (1 to 20) and selected optimal K (5).
Evaluated using accuracy and confusion matrix.


Decision Boundary Visualization:
Visualized decision boundaries using PetalLengthCm and PetalWidthCm.



Files

iris_knn_classification.ipynb: Jupyter Notebook with preprocessing, EDA, and KNN implementation.
Iris.csv: Original Iris Dataset.
Iris_Cleaned.csv: Preprocessed dataset.
class_distribution.png: Bar plot of class distribution.
pairplot.png: Pairplot of features by species.
k_tuning.png: Train vs. test accuracy by K.
confusion_matrix.png: Confusion matrix for KNN (K=5).
decision_boundary.png: Decision boundary visualization.
interview_questions.md: Answers to provided interview questions.
README.md: This documentation file.

Tools Used

Python 3
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
scikit-learn

How to Run

Clone this repository:git clone https://github.com/your-username/Iris-KNN-Classification.git


Install required dependencies:pip install pandas numpy matplotlib seaborn scikit-learn jupyter


Launch Jupyter Notebook:jupyter notebook


Open iris_knn_classification.ipynb and run all cells to:
Generate the cleaned dataset (Iris_Cleaned.csv).
Save visualizations (class_distribution.png, pairplot.png, k_tuning.png, confusion_matrix.png, decision_boundary.png).
Display model metrics.



Observations

EDA: The dataset is balanced (50 samples per class). PetalLengthCm and PetalWidthCm are highly discriminative, especially for Setosa.
KNN Performance: Optimal K=5 achieves high accuracy. Setosa is perfectly classified, with minor confusion between Versicolor and Virginica.
Decision Boundaries: Clear separation for Setosa, with some overlap between Versicolor and Virginica in the 2D feature space.
Normalization: Critical for KNN due to distance-based calculations.

Submission
This repository is submitted for Task 6 of the Elevate AI & ML Internship, completed on July 1, 2025, within the 10:00 AM to 10:00 PM submission window.
