# Practical-Application-3-Python-ML-AI
# Project Summary: What Drives a client to subscribe to a term deposit? 
---

## Objective

Identify the key factors that influece clients to subscribe to a term deposit so that so that the bank can optimize future marketing campaigns, and reduce costs.

---

## Summary of Findings

Following the CRISP-DM Framework, I prepared, cleaned, and analyzed the dataset, then applied multiple regression models to evaluate low MAE. After selecting the best model, I identified the primary drivers of car prices.  

I discovered:
- Car age: Prices decline as cars get older.
- Odometer (mileage): More miles = lower price, with sharper declines at specific thresholds.
- Annual usage: Cars with higher yearly mileage and over 150k total miles show significantly reduced prices.

---

## Next Steps & Recommendations

- Prioritize newer, lower-mileage cars for inventory.
- Discount or move cars over 150k miles more quickly.
- Incorporate the model’s average error (~6,585 MAE) into pricing strategy to account for variation.
- Extend analysis by adding categorical features (make, model, body type, drive, condition) to uncover more price drivers.

---

## Jupiter Notebook
[View Jupiter Notebook](https://github.com/creyes25/Practical-Application-2-Python-ML-AI/blob/main/prompt_II.ipynb)