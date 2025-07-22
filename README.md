## Bank Marketing Prediction Project

[View the notebook](https://github.com/jpistoriusp/Comparing_Classifiers/blob/main/Comparing_Classifiers2.ipynb)

Data Source:

[Bank Marketing Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing)

### Project Overview

This project uses historical marketing data from a Portuguese bank to predict whether a customer will subscribe to a term deposit. The bank contacted clients by phone, and this dataset includes customer information, details of past campaigns, and whether the client eventually signed up for the deposit.

I tested and compared four different models to see which could best predict the outcome:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)

### What I Found

- Most customers do not sign up — only about 11% say "yes", making this a tough prediction problem.
- Logistic Regression and SVM were the most accurate, both scoring around 88.7% accuracy.
- Logistic Regression was much faster to train, making it more practical for real-world use.
- Decision Tree and KNN also performed reasonably well, but with slightly lower accuracy.
- All models had a hard time correctly predicting the small number of "yes" outcomes, which suggests we need to improve how the models handle imbalanced data.

### Improvements Made

I tested ways to improve the models by:
- Trying different settings (like how many neighbors to use in KNN)
- Using better evaluation methods — not just accuracy, but also how well the models identify the "yes" cases
- Planning for future techniques like balancing the dataset and using advanced models

### Final Recommendation

Logistic Regression is currently the best choice for this task due to its strong performance and speed. But because the data is so imbalanced, future work should focus on better identifying customers who are likely to say "yes." This would help the bank focus its marketing efforts more effectively.



