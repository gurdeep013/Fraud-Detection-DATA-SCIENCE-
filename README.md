# 🚨 Fraud Detection • ML Case Study  

A hands-on project where I built an **end-to-end fraud detection system** on a real-world dataset of **6M+ transactions**.  
Goal: turn messy data into smart predictions, insights, and deployable strategies.  

---

## 📥 Download Dataset  
Access the CSV for your own experiments:  
[Download the dataset (Google Drive)](https://drive.google.com/file/d/12yNYAc6scY4haBZzF8MQstJmT0ZBTBRi/view?usp=sharing)  

---

## ✨ Highlights at a Glance  
- **Data Cleaning & Preprocessing:** Handling missing values, trimming outliers, addressing multicollinearity  
- **Feature Engineering:**  
  - Transaction velocity (`secs_since_prev`)  
  - Log transformation of amounts (`amount_log`)  
  - Temporal features: hour, weekday  
- **Models Explored:** Logistic Regression | Random Forest | LightGBM (final)  
- **Evaluation Strategy:** ROC AUC, PR AUC, threshold tuning aligned with business goals  
- **Interpretability:** Feature importance + SHAP for model transparency  
- **Recommendations for Production:**  
  - Real-time scoring + hybrid rules + ML  
  - Adaptive thresholds per segment  
  - Monitoring & feedback loop  

---

## 📂 Project Structure  
```
fraud-detection/
│
├── notebooks/
│   └── Fraud_Detection_Submission_Gurdeep.ipynb   # Full analysis & modeling notebook  
├── summary/
│   └── Fraud_Detection_1Page_Summary_Gurdeep.pdf  # One-page executive summary  
├── artifacts/                                     # Saved models, feature lists, pipelines  
└── README.md                                      # This file
```

---

## 🧠 What You’ll Learn  
- Why **data quality matters** more than algorithms  
- How **small, domain-driven features** can outperform generic ones  
- Why **business-aligned metrics** (like PR AUC & precision@recall) are more meaningful than accuracy  
- How to combine **interpretability (SHAP)** with predictive performance  

---

## 🛠️ Tech Stack  
- **Languages:** Python, SQL  
- **ML & Libraries:** scikit-learn, LightGBM, SHAP  
- **Visualization:** Matplotlib, Seaborn  
- **Workflow & Utilities:** Jupyter Notebook, Joblib  

---

## 👤 About Me  
**Gurdeep Singh**  
Data Analyst & Aspiring Data Engineer  
Skilled in SQL, Python, AWS & GCP  
Turning data into impact through insights, models — and a bit of creativity  

Let’s connect: [LinkedIn](https://www.linkedin.com/) 🚀  
