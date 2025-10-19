 African Cichlid Machine Learning Project
 Overview

This project focuses on predicting care difficulty and analyzing relationships between various traits of African cichlids using multiple machine learning algorithms.
It combines regression, classification, and KNN-based prediction models to understand how species traits such as aggression, activity level, size, and environmental preferences relate to overall care requirements.

The dataset was manually created through detailed research on African cichlid species to ensure realistic behavioral and environmental attributes. This project showcases end-to-end ML development — from data creation and preprocessing to model training, visualization, and evaluation.

 Key Features

Custom-built dataset of African cichlid species

Models used:

Linear Regression – to predict care difficulty and tank size

Logistic Regression – for classifying care levels

Random Forest Classifier

K-Nearest Neighbors (KNN) – to compare classification accuracy

Data preprocessing with:

One-Hot Encoding

StandardScaler

Train/Test split

Visualizations:

Correlation heatmaps

Residual plots

Scatter plots showing predicted vs actual values

 Model Evaluation

Each model was trained and evaluated using R² and Mean Squared Error (MSE) for regression, and accuracy for classification.
Results showed that the regression models captured strong relationships between features and care difficulty, while KNN and Random Forest provided high classification accuracy when predicting care levels.

 Insights

Aggression and activity levels strongly influenced overall care difficulty.

Environmental preferences (temperature, pH, and hardness) were key predictors for tank requirements.

Random Forest and KNN performed best in classification tasks.

 Tools & Libraries

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

 Future Improvements

Add a user input system that suggests compatible species for a user’s tank.

Expand dataset beyond 200 species for stronger model generalization.

Experiment with neural networks for advanced pattern recognition.

 Personal Note

This project marks one of my first major steps into machine learning and data analysis.
It was created independently as part of my journey toward becoming an AI/ML Engineer, combining research, data design, and algorithm experimentation.
