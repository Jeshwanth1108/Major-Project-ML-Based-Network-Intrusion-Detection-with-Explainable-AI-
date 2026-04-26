# 🚀 Machine Learning-Based Network Intrusion Detection System

## 📌 Overview
This project presents a Machine Learning-based Intrusion Detection System (IDS) designed to classify network traffic as **Normal** or **Intrusion (Attack)**.  
It overcomes limitations of traditional signature-based systems by detecting unknown and evolving threats using data-driven approaches.

---

## 🎯 Objectives
- Build an intelligent IDS using Machine Learning
- Handle imbalanced data using SMOTE
- Compare multiple ML models
- Improve detection performance using evaluation metrics
- Add explainability using SHAP and LIME

---

## 📊 Dataset
- Network traffic dataset with flow-based features
- Contains both **normal and attack records**
- Includes features like:
  - Flow duration
  - Packet statistics
  - Protocol type
  - Traffic behavior metrics

---

## ⚙️ Data Preprocessing
- Removed irrelevant features (IP, Flow ID)
- Handled missing and infinite values
- Feature encoding and scaling
- Applied **SMOTE** to handle class imbalance

---

## 🤖 Models Used
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- XGBoost
- LightGBM
- CatBoost

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

## 🧠 Explainable AI (XAI)
- **SHAP** → Feature importance & global interpretation  
- **LIME** → Local prediction explanation  

---

## 📊 Results
- Ensemble models (Random Forest, XGBoost, LightGBM, CatBoost) performed best  
- SMOTE improved minority class detection  
- High ROC-AUC indicates strong classification performance  

---

## 🏁 Conclusion
The system effectively detects network intrusions with high accuracy and interpretability, making it suitable for real-world cybersecurity applications.

---

## 🔮 Future Scope
- Real-time intrusion detection system  
- Deep learning models (LSTM, CNN)  
- Deployment using APIs or cloud platforms  
- Real-time monitoring dashboard  

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost, LightGBM, CatBoost
- SHAP, LIME
- Matplotlib, Seaborn

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook
