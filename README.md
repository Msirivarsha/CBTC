# CBTC
This repository contains implementations of two machine learning models for different tasks: Iris flower classification and spam email detection.
## Iris Flower Classification
The Iris flower classification model predicts the species of iris flowers based on their sepal
and petal dimensions. It implements three different machine learning algorithms: Logistic
Regression, Decision Tree Classifier, and K-Nearest Neighbors (KNN) Classifier.    

### Files
* iris.ipynb: Jupyter notebook containing data exploration, model training, and evaluation for Iris
flower classification.
* deploy.py: Flask web application for deploying the trained model for predictions.
* iris.csv: Dataset containing sepal and petal measurements of iris flowers (included in the
repository).
* templates/index.html: HTML template for the Flask web application.
* model.sav: Serialized model file stored using pickle.
## Spam Email Detection

The spam email detection model identifies emails as spam or ham (non-spam) based on their content. It employs a text preprocessing pipeline and utilizes Logistic Regression, Support Vector Machine (SVM), Decision Tree, and KNN classifiers.

### Files
* email.ipynb: Jupyter notebook for data preprocessing, model training, and evaluation for spam
email detection.
* Spam Email.csv: Dataset containing labeled email messages (spam or ham). This dataset is used
for training and evaluation.
* transformed_text: Processed text column after preprocessing.
