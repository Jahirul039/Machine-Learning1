# Machine-Learning1
# Random Forest Feature Importance — Telco Customer Churn

**Author:** Khondakar Jahirul Islam | Student ID: 24152955 | University of Hertfordshire

A tutorial showing how to use Random Forest Feature Importance (MDI) to identify the key drivers of customer churn and translate them into business insights.

---

## What's Inside

- Data preprocessing (one-hot encoding, handling missing values)
- Training a `RandomForestClassifier` (100 trees, max_depth=10)
- Extracting and visualising feature importances
- Business interpretation of top churn drivers

## Key Findings

- **Tenure** and **Month-to-month contracts** are the two dominant churn drivers
- Churn spikes in the first 1–5 months of service
- Retention efforts should focus on the first 6 months of month-to-month customers

## Setup

```bash
pip install pandas scikit-learn matplotlib seaborn
python src/churn_analysis.py
```

## References

- Breiman, L. (2001). *Random Forests*. Machine Learning, 45(1), 5–32.
- Pedregosa et al. (2011). *Scikit-learn*. JMLR, 12, 2825–2830.
- [scikit-learn Feature Importance docs](https://scikit-learn.org/stable/modules/ensemble.html#feature-importance-evaluation)
