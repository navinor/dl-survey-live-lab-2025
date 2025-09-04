# Experiment Log — Taiwo 

## Run 1 — 2025-09-04
- **Goal / Question**: What happens if I change `n_estimators` from 100 to 200?
- **Setup**: Baseline Random Forest, train/test split = 80/20
- **Results**: Accuracy = 0.84, Precision = 0.72, Recall = 0.66
- **Reflection**: Increasing estimators gave a small accuracy bump. Took longer to train. Worth it? Maybe.

---

## Run 2 — 2025-09-06
- **Goal / Question**: Compare Random Forest vs Logistic Regression
- **Setup**: Same preprocessing as before
- **Results**: RF Acc = 0.85, LogReg Acc = 0.79
- **Reflection**: LogReg underfit the data. Nice reminder that not all models capture interactions.
