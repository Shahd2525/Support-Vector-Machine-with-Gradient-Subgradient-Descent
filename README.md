Project Title

Support Vector Machine with Gradient & Subgradient Descent

Description

This project implements a Support Vector Machine (SVM) from scratch using both gradient descent and subgradient descent optimization methods to classify banknote authentication data. The model was trained on the UCI Banknote Authentication dataset, which contains statistical features (variance, skewness, kurtosis, and entropy) extracted from images of genuine and forged banknotes.

The workflow included:

Data Preparation: Cleaning, removing duplicates, scaling features, and splitting into training, validation, and test sets.

Exploratory Data Analysis: Visualizing feature correlations and class separability using heatmaps and pairplots.

Model Development: Implemented hinge-loss based SVM optimization using:

Subgradient Descent for non-differentiable hinge loss.

Gradient Descent for differentiable approximations.

Evaluation: Compared accuracy, loss curves, and confusion matrices between the two methods.

Results

Both optimization methods achieved high accuracy in classifying real vs. fake banknotes.

Analysis of learning curves showed convergence behavior and performance differences between gradient and subgradient approaches.

Demonstrated strong understanding of machine learning fundamentals, optimization algorithms, and practical model evaluation.

Skills Demonstrated

Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)

Machine Learning theory (SVM, hinge loss, gradient methods)

Data preprocessing and visualization

Model evaluation and performance analysis
