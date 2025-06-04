# Elevate-Labs-Task-06

In the above Taskfolder you can find all the necessary files regarding Task 6. In the Jupyter file 'task6_solutions.ipynb', I have implemented KNN classifier analyzes Iris dataset to classify the Flower Spicies. I have mainly used the scikit learn library in python for creating the KNN classifier and for evaluating it in the following manner.

#### Data preprocessing: 
Loaded and explored the Iris dataset.Removed irrelevant 'Id' column.Encoded categorical labels (Species) into numerical values.Standardized features using Z-score normalization.

#### Model Trainig: 
Split data into training (70%) and testing (30%) sets.Implemented K-Nearest Neighbors classifier with initial K=5.

#### Hyperparameter optimization: 
Tested K values from 1 to 30.Evaluated performance using test accuracy.Identified optimal K value as 3 with highest accuracy.

#### Model evaluation: 
Calculated overall classification accuracy.
Generated confusion matrix to analyze class-specific performance.

#### Decision Boundary visualization:
Optimal K: K=3 \
Classification Performance: \
Perfect separation for Iris-setosa and Iris-virginica \
Minor confusion (1 misclassification) between Iris-versicolor and Iris-virginica \
Feature Importance: \
Petal measurements are most discriminative \
Sepal measurements provide supplementary separation power
