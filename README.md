
# 🌲 Ensemble Learning – Bagging & Random Forest

- Objective: Improve prediction performance using ensemble techniques
- Techniques Covered:
  - Bagging (Bootstrap Aggregating)
  - Random Forest
  - Out-of-Bag (OOB) Evaluation
- Tasks Implemented:
  - Classification
  - Regression

---

## 🌳 Bagging Classifier

- Dataset: (Mention dataset name)
- Base Estimator: Decision Tree
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - OOB Score (if enabled)

### Key Observations

- Reduces variance compared to single Decision Tree
- Improves stability of predictions
- Handles overfitting better than standalone model
- Performance improves as number of estimators increases

---

## 🌲 Random Forest Classifier

- Dataset: (Mention dataset name)
- Number of Trees: (n_estimators value)
- Features per Split: (max_features value)
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - OOB Score

### Key Observations

- Feature randomness reduces correlation between trees
- Better generalization than Bagging alone
- More robust to noise
- Handles high-dimensional data efficiently

---

## 📈 Bagging Regressor

- Dataset: (Mention dataset name)
- Base Estimator: Decision Tree Regressor
- Evaluation Metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
  - OOB Score

### Key Observations

- Reduces variance in regression predictions
- Produces smoother prediction curve
- Less sensitive to outliers compared to single tree

---

## 🌳 Random Forest Regressor

- Dataset: (Mention dataset name)
- Number of Trees: (n_estimators value)
- Features per Split: (max_features value)
- Evaluation Metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
  - OOB Score

### Key Observations

- Better bias-variance tradeoff
- Higher R² compared to single Decision Tree
- Stable performance across different data splits

---

## 🛠 Out-of-Bag (OOB) Evaluation

- Enabled using: oob_score = True
- Purpose:
  - Provides internal validation
  - Eliminates need for separate validation set
  - Gives unbiased estimate of performance
- Works only when bootstrap = True

---

## 🏷 Classification Models

- Bagging Classifier
- Random Forest Classifier

- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - OOB Score

---

## 📈 Regression Models

- Bagging Regressor
- Random Forest Regressor

- Evaluation Metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
  - OOB Score

---

## 📊 Model Evaluation

Ensemble models were evaluated based on:

- Prediction performance
- Bias-variance tradeoff
- OOB score stability
- Generalization capability

Random Forest generally outperformed standalone Decision Trees due to feature randomness and ensemble averaging.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 👩‍💻 Author

**Vaishnavi Rathi**

---
