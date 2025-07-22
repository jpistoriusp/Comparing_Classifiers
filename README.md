I chose a fraud detection dataset because it represents a real-world challenge with serious impact. Insurance fraud is a major problem for companies, costing billions of dollars each year. Being able to spot potentially fraudulent claims early can save time, money, and help honest customers get faster service.

This type of project allowed me to:
- Work with imbalanced data, which is common in real scenarios.
- Explore patterns in human behavior, policy details, and claim types.
- Practice building a machine learning model to predict yes/no outcomes (fraud or not fraud).

It’s a meaningful and practical application of data science that can make a real difference.



#### Why Use Logistic Regression?

We started with a model called Logistic Regression for a few important reasons:

- Easy to Understand:  
  It gives clear information about which parts of a claim (like damage severity or incident type) are most related to fraud.

- Built for Yes/No Predictions:  
  Since we’re trying to predict whether a claim is **fraud or not**, this model is a perfect fit.

- Good Starting Point:  
  This model is simple and fast, so we used it as a starting point to compare against more advanced models later.

- Handles Imbalanced Data:  
  Most of the claims in our dataset were not fraud, and this model lets us adjust for that so it doesn’t ignore the rare fraud cases.

---------------------------------------------------

#### How I Measured Success

Because fraud is rare, a model that just says “not fraud” all the time might look accurate — but would be useless. So instead of just looking at overall accuracy, we focused on a few key measurements:

Precision: When the model says a claim is fraud, how often is it right? Helps avoid falsely accusing good claims. |
Recall: How many actual fraud cases did the model catch? This is especially important so real fraud doesn't slip through. |
F1 Score: A balanced score that looks at both precision and recall together. |
Confusion Matrix: A simple chart that shows how many claims were correctly or incorrectly labeled. |

In short: We cared most about how well the model could catch fraud without wrongly flagging too many honest claims. Even though it's not perfect, it gives us a clear foundation to build better models later.
