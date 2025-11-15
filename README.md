# Practical-Application-3-Python-ML-AI
# Project Summary: What Drives a Client to Subscribe to a Term Deposit? 
---

## Objective

Identify the key factors that influece clients to subscribe to a term deposit so that so that the bank can optimize future marketing campaigns and reduce operational costs. Multiple classification algorithms(Logistic Regression, KNN, Decision Tree, SVM), were compared to determine which model performs best and provide insights that can help optimize future marketing campaigns. 

---

## Summary of Findings


Following the CRISP-DM Framework, I prepared, cleaned, and analyzed the dataset, then applied multiple classification models to compare performance. Logistic Regression and Decision Trees gave the best results, both reaching 0.897 accuracy with fast training time and strong generalization. KNN offered slightly lower accuracy and significantly slower training time, while SVM was too computationally expensive for this dataset when combined with one-hot encoding and cross-validation.

These results show that simple, well-regularized models are highly effective for predicting term deposit subscriptions. The bank can use these insights to more efficiently target clients who are most likely to subscribe, improving campaign efficency and reducing costs.

Key Insights:
- Most clients do not subscribe
  - The dataset is highly imbalanced with the majority of clients responding "no" to a term deposit. 
- Call duration strongly predicts subscription
  - Longer calls correlate heavily with a successful subscription However, duration is only known after a call happens, but this variable was removed to avoid unrealistic model performance.
- Economic indicators influece client decisions:
  - Features such as euribo3m, employmenent variation rate, and consumer price index show noticeable correlations with subscription behavior. Suggesting that economic conditions influece whether clients commit to long-term deposits. 

---

## Next Steps & Recommendations


- Improve handling of class imbalance. The dataset contained more "no" responses than "yes" which affects model performance.
- Evaluate additional performance metrics by using precision, recall, F1 score. 
- Experiment with additional models such as Random Forest. 
- Tune heavy models on smaller samples
  - SVM was computationally heavy on a the full dataset.

---

## Jupiter Notebook
[View Jupiter Notebook](https://github.com/creyes25/Practical-Application-3-Python-ML-AI)