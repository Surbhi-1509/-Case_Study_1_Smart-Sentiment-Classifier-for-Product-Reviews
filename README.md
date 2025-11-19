# -Case_Study_1_Smart-Sentiment-Classifier-for-Product-Reviews

📘 Overview
This project automatically classifies customer reviews as positive, negative, or neutral. It demonstrates a practical NLP pipeline—preprocessing → TF–IDF → model training → evaluation → inference—and delivers a reusable predict_sentiment() helper for quick predictions.

🧩 Problem Statement
Online marketplaces generate massive review volumes. Manual reading is slow and inconsistent. We build an automated classifier to:

monitor customer satisfaction,
surface actionable insights,
and support data-driven improvements.
🎯 Objectives
Clean and normalize raw review text.
Convert text to numeric features via TF–IDF (unigrams + bigrams).
Train and compare Logistic Regression, Linear SVM, Random Forest.
Evaluate with Accuracy, F1-score, and Confusion Matrix.
Expose a predict_sentiment() function for real-time predictions.
🧪 Methodology
Dataset: Product_Reviews.csv
Preprocessing: lowercasing, removing punctuation, digits, and URLs.
Features: TF–IDF vectorization with n-grams (1,2).
Models: Logistic Regression, Linear SVM, Random Forest.
Evaluation: accuracy, macro/weighted F1, confusion matrix; error analysis on misclassifications.

📊 Results (Typical)
Top model: Logistic Regression (most consistent accuracy and F1 across classes).
Insight: Simple linear models + TF–IDF capture sentiment cues effectively.
Next steps: Review misclassified cases to refine preprocessing and class balance.
Note: Exact scores depend on your data split/seed.
