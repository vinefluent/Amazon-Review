# Amazon Fine Food Reviews Analysis

This project aims to perform sentiment analysis on Amazon Fine Food Reviews dataset obtained from [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews). The dataset contains reviews of fine foods from Amazon spanning from October 1999 to October 2012. It consists of 568,454 reviews from 256,059 users on 74,258 products. Each review has 10 attributes including the product ID, user ID, review summary, review text, and more.

## Objective 🚀

The main objective of this project is to determine whether a review is positive (rating of 4 or 5) or negative (rating of 1 or 2) based on the review text and related attributes. 

## Attribute Information ℹ️

1. **Id**: Unique identifier for the review
2. **ProductId**: Unique identifier for the product
3. **UserId**: Unique identifier for the user
4. **ProfileName**: Name of the user profile
5. **HelpfulnessNumerator**: Number of users who found the review helpful
6. **HelpfulnessDenominator**: Number of users who indicated whether they found the review helpful or not
7. **Score**: Rating between 1 and 5
8. **Time**: Timestamp for the review
9. **Summary**: Brief summary of the review
10. **Text**: Text of the review

## Analysis Steps 🔍

**Exploratory Data Analysis (EDA)**: 
- Analyze the dataset to gain insights and understand the distribution of reviews, users, and products. This is our prime focus as a contributor.

**t-SNE (t-distributed Stochastic Neighbor Embedding)**: 
- Visualize high-dimensional data to identify patterns and clusters.

**K-Nearest Neighbors (KNN)**: 
- Implement KNN algorithm to classify reviews based on similarities.

**Naive Bayes**: 
- Apply Naive Bayes classifier for sentiment analysis.

**Logistic Regression**: 
- Utilize logistic regression for binary classification of reviews.

**Support Vector Machine (SVM)**: 
- Implement SVM algorithm for sentiment analysis.

**Decision Tree**: 
- Build a decision tree model to classify reviews.

**Random Forest and XGBoost**: 
- Implement ensemble methods to improve classification accuracy.

## About ℹ️

Amazon Fine Food Reviews project addresses a sentiment analysis classification problem. It aims to classify reviews into positive and negative sentiments based on user ratings and review text. The project features data exploration and application of various machine learning techniques to analyze and classify reviews effectively.
