# High-Value Customer Predictor

### 1. Why this matters
We want to spot shoppers who are likely to spend **SAR 5 000 or more next quarter** so marketing can send fewer, smarter emails and make more money.

---

### 2. What’s inside the notebook
* **Data:** 2 k+ retail customers, Jan 2023 – Apr 2025  
* **Steps:** quick clean-up → a few new features → three models (Logistic, KNN, RandomForest) → 80/20 test split  
* **Metric:** F1 score (balance between precision & recall)

---

### 3. Three things we learned
1. **RandomForest is best** – F1 ≈ 0.92  
2. **All models are solid** – even the simplest scores ≥ 0.89  
3. **Logistic is the backup** – almost as good and easy to explain

---

### 4. What to do next
* **Pilot:** email the top-20 % customers the model ranks highest, compare sales against a control group  
* **Refresh:** retrain the model once a month to stay current  
* **Broaden:** add in-store purchase data to catch offline spenders
