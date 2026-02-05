Iris Flower Classification using Machine Learning
📌 Project Overview

This project implements a multiclass classification system to identify Iris flower species (Setosa, Versicolor, Virginica) based on sepal and petal measurements. The goal is to compare linear and distance-based machine learning models and evaluate their performance using proper classification metrics.

📂 Dataset

Name: Iris Dataset

Samples: 150

Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

Target Variable: Species (3 classes)

The Id column was removed as it does not contribute to prediction.

🛠️ Tools & Libraries

Python

Pandas

NumPy

Scikit-learn

Matplotlib

🔍 Methodology

Data cleaning and preprocessing

Removal of non-informative features

Label encoding of target classes

Stratified train-test split

Feature scaling using StandardScaler

Model training and comparison:

Logistic Regression

K-Nearest Neighbors (KNN)

Model evaluation using accuracy, confusion matrix, and classification report

Hyperparameter tuning for KNN

📊 Model Performance
Logistic Regression

Accuracy: 93%

Perfect classification of Setosa

Minor confusion between Versicolor and Virginica

KNN (K = 5)

Accuracy: 93%

Improved precision for some classes

Lower recall for Virginica

Tuned KNN (K = 7)

Accuracy: 97%

Reduced misclassification

Better class-wise balance

This demonstrates the bias–variance tradeoff and the importance of hyperparameter tuning.

🧠 Key Learnings

Accuracy alone is not sufficient for model evaluation

Confusion matrices provide deeper insight into class-wise performance

Feature scaling is critical for distance-based algorithms

Hyperparameter tuning significantly improves generalization

✅ Conclusion

Both Logistic Regression and KNN performed well on the Iris dataset. However, tuning the number of neighbors in KNN improved overall accuracy and reduced class-wise errors, making it the best performing model for this task.
