# 🍄 Mushroom Classification using Machine Learning

## 📌 Project Description

This project implements a Mushroom Classification System using machine learning algorithms.

The goal is to classify mushrooms as edible (safe) or poisonous (toxic) based on their physical characteristics (cap shape, color, odor, gill size, etc.).

The model is trained on the Mushroom Dataset to demonstrate supervised classification.

## 📂 Dataset

Dataset used: UCI Mushroom Dataset (or synthetic mushroom dataset if custom)

Features include:

cap-shape

cap-surface

cap-color

odor

gill-size

habitat

... and more categorical attributes

Target column: class

e = edible

p = poisonous

## ⚙️ Requirements

Install the following Python libraries before running the code:

pandas

numpy

matplotlib

seaborn

scikit-learn

pickle (for saving/loading models)

## ▶️ How to Run

Clone the repository or download the files.

Place the dataset (mushrooms.csv) in the same directory.

Open and run the Jupyter Notebook:

jupyter notebook mushroom.ipynb


The notebook performs:

Data exploration (EDA)

Preprocessing (label encoding categorical features)

Train-test split

Training with Naïve Bayes / Decision Tree / Random Forest

Model evaluation (accuracy, confusion matrix, ROC curve)

Saving the model using pickle

## 📊 Results

The classifier achieved high accuracy in predicting edible vs. poisonous mushrooms.

Evaluation metrics used:

✅ Accuracy Score

✅ Precision, Recall, F1-score

✅ Confusion Matrix

✅ ROC Curve & AUC Score

## 📝 Conclusion

Machine learning can successfully classify mushrooms as edible or poisonous based on physical features.

Naïve Bayes / Random Forest works well for this dataset.

## 🚀 Future Development

Try different ML models (Logistic Regression, Gradient Boosting, XGBoost).

Perform feature importance analysis to see which attributes are most predictive.

Build a Flask/Streamlit web app for real-time mushroom classification.
