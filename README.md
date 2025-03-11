🔗 **Read my LinkedIn post for more details and insights:**  
[How Probability Threshold Impacts Classification Models](https://www.linkedin.com/posts/vinicius-maiolo_logistic-regression-optimization-diabetes-activity-7305195374216962050-Qy3l?utm_source=share&utm_medium=member_desktop&rcm=ACoAADcUjh0BXS20aF6xOGUNxUUPSBQ9s8hlSQc)  

# 🎯 How Does the Probability Threshold Impact Classification Model Performance?

Choosing the right probability threshold is crucial in classification models—it directly affects precision, recall, and the trade-off between false positives and false negatives.

## 📌 Project Overview
In this project, we built a **Logistic Regression** model for **Diabetes Diagnosis** and tested two probability thresholds:

- ✅ **Model 1 (Threshold = 50%)** → Higher **precision (73.58%)**, but missed many positive cases (**FNR = 41.79%**).
- ✅ **Model 2 (Threshold = 30%)** → Higher **recall (80.97%)**, capturing more real positive cases, but increasing false positives (**FPR = 28.60%**).

## 📊 Model Comparison

| Metric                   | Model 1 (50%) | Model 2 (30%) |
|--------------------------|--------------|--------------|
| **Threshold**            | 50%          | 30%          |
| **Precision**            | 73.58%       | 60.28%       |
| **Sensibility (TPR)**    | 58.21%       | 80.97%       |
| **Specificity (TNR)**    | 88.80%       | 71.40%       |
| **False Positive Rate**  | 11.20%       | 28.60%       |
| **False Negative Rate**  | 41.79%       | 19.03%       |

## 🔍 Key Takeaways:
- 📌 Lower thresholds improve recall but reduce precision.
- 📌 Higher thresholds reduce false positives but risk missing real cases.
- 📌 The best threshold depends on the **business goal**—do we prioritize detecting positives or avoiding false alarms?
