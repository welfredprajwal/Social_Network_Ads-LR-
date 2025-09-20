# Social Network Ads Prediction Using Logistic Regression

# Overview

This project builds a Logistic Regression model to optimize ad targeting for a social media platform.

By analyzing user behavior, the model predicts whether a user is likely to engage with a particular ad. Features like Age and Estimated Salary are used because older, wealthier users tend to engage more with the ad.


# Dataset

The dataset contains the following columns:


| Column Name         | Type        | Description                                              |
| ------------------- | ----------- | -------------------------------------------------------- |
| **User ID**         | Numeric     | Unique identifier for each user (not used for modeling)  |
| **Gender**          | Categorical | Male/Female                                              |
| **Age**             | Numeric     | Age of the user                                          |
| **EstimatedSalary** | Numeric     | Estimated yearly salary of the user                      |
| **Purchased**       | Target      | 1 = Purchased ad / engaged with ad, 0 = Did not purchase |


# Workflow

1.Data Preprocessing

  Encode categorical features (e.g., Gender → 0/1)
  Handle missing values (if any)
  Feature scaling for Age and EstimatedSalary

2.Train-Test Split

  Split data into training and testing sets (e.g., 80% train, 20% test)

3.Model Training

  Train a Logistic Regression classifier
  Use the model to predict the likelihood of a user purchasing the ad

4.Evaluation

  Accuracy, Confusion Matrix, Precision, Recall, F1-score
  Visualize decision boundary to understand model predictions

5.Prediction

  Predict new user engagement probabilities for ad targeting

# Results

After training and testing the Logistic Regression model, the following results were observed:

Accuracy

Model Accuracy: ~89–92%

