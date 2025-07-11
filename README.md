# YoungDevInterns_Artificial-Intelligence_Task_3
 Create a Basic Classification Model  Task: Develop a simple classification model.  Details:  Use a dataset like Iris to classify data points.  Train a model using a classification algorithm such as Logistic Regression or Decision Tree

📌 Task Objective
This project demonstrates how to develop a basic classification model using Logistic Regression to categorize cereal ratings into:

Low

Medium

High

This is part of the YoungDev AI & ML Internship tasks.

📊 Dataset
File: preprocessed_cereal.csv

Target: rating (converted into categorical rating_class)

Features include various nutritional information (calories, sugar, protein, etc.)

🧠 Steps Implemented
Preprocessing

Converted the continuous rating column into 3 categories using pd.cut()

Encoded class labels with LabelEncoder

Model Training

Split dataset into train/test sets

Trained a Logistic Regression classifier (LogisticRegression from sklearn)

Model Evaluation

Computed accuracy score

Displayed confusion matrix using ConfusionMatrixDisplay
