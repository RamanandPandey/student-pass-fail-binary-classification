# 🎓 Student Pass/Fail Prediction

Binary classification project predicting student exam outcomes using Logistic Regression.

## 📌 Pipeline
Data Loading → EDA → Preprocessing → Model Training → Evaluation

## 📊 Dataset
- 10,000 student records, 23 features
- Target: `pass_fail` (Binary — Pass / Fail)
- Features: exam scores, GPA, attendance, study hours, demographics

## 🔍 EDA Highlights
- Correlation heatmap across all numerical features
- Histogram, Boxplot & KDE plots for distribution analysis
- Key finding: Final exam score & previous GPA most correlated with outcome

## 🤖 Model
- **Algorithm:** Logistic Regression (Scikit-learn)
- **Split:** 80% Train / 20% Test
- **Evaluation:** Accuracy, Confusion Matrix, Classification Report

## 🛠️ Tech Stack
Python · NumPy · Pandas · Matplotlib · Seaborn · Scikit-learn

## 🚀 Run
```bash
git clone https://github.com/YOUR_USERNAME/student-pass-fail-binary-classification.git
jupyter notebook
```

## 💡 Future Improvements
- Feature scaling
- Try Random Forest, XGBoost, SVM
- Cross-validation & hyperparameter tuning

- ##Author
- Ramanand Pandey
