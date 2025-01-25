# **Sentiment Analysis of Amazon Product Reviews: Predicting Customer Satisfaction**

## **Project Overview**

This project analyzes over 34,000 Amazon product reviews to predict customer satisfaction using sentiment analysis, classification models, and topic modeling techniques. It addresses challenges like class imbalance, effective feature engineering, and evaluation of model performance.

## **Objectives**

Understand and predict sentiments expressed in Amazon product reviews.

Address class imbalance to improve model accuracy.

Compare traditional machine learning algorithms with neural network approaches.

Extract actionable insights using topic modeling techniques.

## **Key Features of the Dataset**

Attributes: Brand, Categories, Review Titles, Review Text, Sentiment Levels (Positive, Neutral, Negative).

Challenges: Class imbalance with a dominance of Positive reviews.

Workflow and Methodology

## 1. Data Preprocessing:

Handled missing values and performed data cleaning.

Engineered new features, such as:

reviews_day, reviews_month, and reviews_year.

Sentiment score for additional insight.

Transformed text data into numerical features using TF-IDF vectorization.

## 2. Class Imbalance Handling:

Applied oversampling to increase minority class representation.

Experimented with undersampling for comparison.

## 3. Model Implementation:

Traditional Machine Learning Models:

Logistic Regression on oversampled data achieved an accuracy of 58.69%.

XGBoost emerged as the best performer, providing balanced predictions across all sentiment categories.

Deep Learning Models:

LSTM models captured long-term dependencies but struggled with minority classes.

ANN showed decent performance but could not surpass XGBoost.

## 4. Topic Modeling:

Used Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF) for clustering reviews into themes.

Key topics included:

Device Durability

Child-Friendly Features

Usability for Reading and Entertainment

## Evaluation Metrics

F1-Score: Focused on balancing precision and recall.

ROC-AUC: Used to gauge model performance across all classes.

Precision, Recall, and Accuracy metrics were also employed for comparison.

## Key Insights and Results

## **Customer Sentiments:**

Positive reviews emphasized ease of use, screen quality, and compatibility with smart devices.

Negative reviews highlighted issues like slow connectivity and poor battery life.

## **Model Performance:**

XGBoost performed best overall, particularly in handling imbalanced data.

Logistic Regression showed improvements with oversampled data but lagged behind XGBoost.

LSTM models provided moderate results, unable to address class imbalance effectively.

## **Topic Modeling:**

Revealed themes related to customer priorities like durability, aesthetics, and performance.

## **Recommendations**

Focus on ensemble-based models like XGBoost for imbalanced datasets.

Enhance product features, especially for child-friendly devices and improved entertainment capabilities.

Use topic modeling insights to align product design and marketing strategies with customer expectations.

Experiment with hybrid models combining XGBoost and LSTM for improved predictions.

## **Learning Outcomes**

Developed expertise in handling class imbalance and feature engineering.

Gained insights into the comparison of machine learning and deep learning models.

Explored topic modeling for extracting latent themes from reviews.

Files Included

Jupyter Notebook/Google Colab File: Contains all the code and implementation details.

Project Summary Report: Provides a comprehensive overview of the project.

Presentation (PPT): Highlights key findings and results.

## **Conclusion**

This project demonstrates the effective application of sentiment analysis techniques to predict customer satisfaction. By addressing class imbalance, leveraging ensemble methods, and extracting actionable insights, it offers valuable recommendations for improving customer experience and product offerings in e-commerce.

Output:
![visualization](https://github.com/user-attachments/assets/9c7d4774-7925-4da7-9d9f-3c727fe55206)
![wordcloud_positive](https://github.com/user-attachments/assets/8dd48001-0082-4129-9926-a263d5b220eb)
![wordcloud_negative](https://github.com/user-attachments/assets/0b7fa352-7411-4bef-8f43-3b0402130096)
![wordcloud_neutral](https://github.com/user-attachments/assets/1babc363-41df-4ddd-ace6-b2fc448467aa)
![undersampling](https://github.com/user-attachments/assets/2166fb0e-ab98-4a27-a681-6a5e0487bcca)
![oversampling](https://github.com/user-attachments/assets/9fabb10d-dc02-4152-9b5f-3c1f9c3ca122)
![Randomforest](https://github.com/user-attachments/assets/c58e292e-60b7-4241-84d1-72ca2b1331bf)
![XGBoost](https://github.com/user-attachments/assets/b938235f-7af6-4cba-98fd-0713cd636ef0)
![LSTM](https://github.com/user-attachments/assets/5584069e-869d-46c3-9709-a83c07b52c51)
![Topic](https://github.com/user-attachments/assets/af88ec33-f2a9-447e-9f31-02a98fabcd31)



