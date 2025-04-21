
# TumorRecurrence_MLModel
This machine learning project predicts the likelihood of thyroid cancer recurrence using clinical and pathological data. The goal is to help healthcare providers identify patients at higher risk of recurrence so they can receive more focused monitoring and treatment.

Data Source: https://www.kaggle.com/datasets/aneevinay/thyroid-cancer-recurrence-dataset

The dataset includes features such as age, tumor staging (TNM), lymph node involvement, cancer subtype, and treatment response. 

Preprocessing:
One-hot encoding was used to preprocess categorical variables, and SMOTE (Synthetic Minority Over-sampling Technique) was applied to address class imbalance.

Models Tested
Decision Trees (3), AdaBoost, and Gradient Boosting, with Gradient Boosting achieving the best performance. The final model was evaluated on unseen test data, achieving high precision and recall, especially in identifying patients who are likely to experience recurrence.
The model is especially strong at minimizing false negatives, ensuring fewer patients with recurrence are missed — a crucial factor in clinical decision-making.

Model Performance on Test Data:
Accuracy: 96.1%
Recall: 86.4%
Precision: 100%
F1-Score: 92.7%

Key predictors included:
Lymph node involvement (N1b)
Structural incomplete response
Higher risk categories
