
# 🏦 Credit Risk Classification

## 📌 Overview

The purpose of this analysis is to evaluate a logistic regression model for predicting credit risk—specifically identifying whether a loan is **high risk (1)** or **healthy (0)**. This classification task is critical for financial institutions to manage loan portfolios effectively and reduce default rates.

---

## 📈 Model Performance Metrics

- **Accuracy:** XX% — Indicates how often the model correctly classified loan risk.
- **Precision:** XX% — Of all loans predicted as high risk, how many were actually high risk?
- **Recall:** XX% — Of all actual high-risk loans, how many did the model correctly identify?

> *(Replace the XX% values with actual metrics obtained from your model output.)*

---

## ✅ Summary & Recommendation

Based on the evaluation of the logistic regression model:

- If **accuracy, precision, and recall are all high** (e.g., >85%), the model is reliable and can be confidently recommended for identifying credit risk.
- If **recall for high-risk loans is low**, the model may fail to identify risky loans, making it unsuitable for deployment in a high-stakes financial environment.

**Recommendation:**
- ✅ Recommend if the model effectively balances recall and precision for high-risk loans.
- ❌ Do not recommend if the model consistently misses high-risk loans (low recall), as this could expose the company to financial loss.

**Justification:** The final recommendation depends on how well the model aligns with the company’s risk tolerance. Prioritizing **recall** may be more important than overall accuracy in this context.

---

