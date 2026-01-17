# Predictive Maintenance: Recall-Optimized Failure Forecasting

A machine learning pipeline designed to detect rare equipment failures in high-imbalance manufacturing datasets.

**Key Objectives:**

- **Minimize Downstream Cost:** Prioritized **Recall** over Accuracy to penalize false negatives (missed failures) more than false positives (unnecessary checks).
- **Interpretability:** Utilized **SHAP values** to engineer features like `Wear_x_Torque` and isolate collinearity between air/process temperatures.
- **Model Stacking:** Implemented a Voting Classifier (Random Forest + XGBoost) to achieve higher Recall.

<img width="3840" height="2880" alt="SPCS-Poster" src="https://raw.githubusercontent.com/ShrootBuck/stanford-predictive-maintenance/refs/heads/main/Poster.png" />
