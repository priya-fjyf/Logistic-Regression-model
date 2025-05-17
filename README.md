# 🚀 Logistic Regression - Binary Classification

This project applies Logistic Regression to predict whether a passenger survived the Titanic disaster based on features like **Age** and **Fare**.

---

## 📌 Features

- Binary classification using Logistic Regression
- Data visualization (including 3D plot)
- Accuracy & classification report
- Model saving using `joblib`

---

## 📂 Dataset

- Titanic dataset (Survived = 0 or 1)
- Features used: `Age`, `Fare`

---

## 🧪 Tech Stack

- Python
- Jupyter Notebook
- Scikit-learn, Pandas, Matplotlib, Joblib

---

## 💾 Model Saving

```python
joblib.dump(model, 'logistic_model.pkl')
