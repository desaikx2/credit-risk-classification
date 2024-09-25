# Module 12 Report Template
### Credit Risk Classification

### Overview of the Analysis

The goal of this analysis is to develop a supervised machine learning model that predicts whether a loan is healthy (class 0) or high-risk (class 1). We will utilize logistic regression as our binary classifier. The analysis focuses on financial data, specifically examining loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The aim is to classify the loan status as either healthy (0) or high-risk (1) using a dataset comprising 77,500 entries in a CSV file.

The machine learning process for this analysis consisted of the following stages:

1. **Data Preparation:** Separating the loan status (healthy or high-risk) as the label and the remaining seven columns as features.
2. **Data Splitting:** Dividing the data into training and testing datasets.
3. **Model Creation:** Building a Logistic Regression model using scikit-learn.
4. **Model Selection:** Choosing logistic regression as a binary classifier to categorize loans into two distinct classes: healthy or high-risk.
5. **Model Fitting:** Training the model using the training dataset.
6. **Making Predictions:** Using the test dataset to generate predictions.
7. **Performance Evaluation:** Assessing the model's effectiveness through accuracy, precision, and recall scores.


### Results

Here are the accuracy, precision, and recall scores for the Logistic Regression model used in this analysis:

**Logistic Regression Model:**
- Accuracy: 100%
- Precision: 87%
- Recall: 89%
- F1-Score : 88%

### Summary

The Logistic Regression model demonstrated strong performance in predicting loan statuses, achieving high accuracy, precision, and recall scores. Based on these results, this model is recommended for use, especially because:

- **Performance:** The model performs well in predicting both healthy and high-risk loans, with balanced precision and recall scores.
- **Problem-Specific Consideration:** If the aim is to minimize financial risk, accurately predicting high-risk loans is essential. The model’s high recall for high-risk predictions indicates its effectiveness in this area.

Overall, the Logistic Regression model is a dependable option for predicting loan status. However, depending on specific requirements (e.g., prioritizing the reduction of false negatives), additional tuning or exploration of alternative models may be advantageous.