# Sentiment Analysis with Machine Learning
This repository contains a simple sentiment analysis project using machine learning. The goal is to classify reviews as positive or negative based on their content.

### Project Overview
The project involves the following key steps:

**1. Data Loading:** The sentiment analysis is performed on a dataset of book reviews. The dataset is loaded from a JSON file.

**2. Fair Distribution:** To ensure a balanced dataset, reviews are evenly sampled from both positive and negative sentiments.

**3. Train-Test Split:** The dataset is split into training and testing sets for model evaluation.

**4. Text Vectorization:** The text data is converted into numerical vectors using TF-IDF vectorization.

**5. Machine Learning Models:**

**Linear SVM:** A Support Vector Machine model with a linear kernel is trained.

**Naive Bayes:** A Gaussian Naive Bayes model is trained.

**Logistic Regression:** A Logistic Regression model is trained.

**6. Model Evaluation:** The models are evaluated based on their accuracy using the testing set.
