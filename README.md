# 🚀 Startup Success Prediction

This project uses machine learning to predict the **success or failure of startup companies** based on early-stage indicators like funding history, location, industry, and product stage.

It was developed as part of the **CSE 523/524 Advanced Project** coursework by Abhay Ravi Kumar.

---

## 📌 Overview

Startups operate in highly uncertain environments, and understanding the early signals of their success can assist investors, accelerators, and analysts in making informed decisions.

Using a dataset of over 28,000 startups, this project applies:

- 📊 Exploratory Data Analysis (EDA)
- 🔧 Feature Engineering (e.g., funding intensity, funding gap)
- 🤖 Machine Learning Models:
  - XGBoost
  - Random Forest
  - CatBoost
  - LightGBM
  - Ensemble (Stacking Classifier)

SMOTE is used to handle class imbalance, and Optuna is integrated for hyperparameter tuning.

---

## 📂 Files

| File                  | Description |
|-----------------------|-------------|
| `Advance_Project.ipynb` | Main notebook with data processing, modeling & results |
| `startup_data.csv`      | Dataset used for training and testing |
| `final_report.pdf`      | Detailed report explaining methodology and outcomes |

---

## 📈 Results

Best model: **Stacking Classifier**

- **Accuracy**: 94.67%
- **F1-Score (Success class)**: 0.84

The final pipeline integrates feature selection, data balancing, standardization, and ensemble learning to deliver strong predictive performance.

---

## 📬 Author

**Abhay Ravi Kumar**  
Stony Brook University  
Email: *[Your Email Here]*  
LinkedIn: *[Your LinkedIn]*

---

## 📜 License

This project is for educational and research use only.
