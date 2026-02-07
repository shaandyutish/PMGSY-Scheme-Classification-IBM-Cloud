# PMGSY (Pradhan Mantri Gram Sadak Yojana) Scheme Classification using IBM Cloud

## 📌 Project Overview
This project presents an intelligent machine learning solution to automatically classify rural road and bridge infrastructure projects under the appropriate **Pradhan Mantri Gram Sadak Yojana (PMGSY)** scheme. The system reduces manual effort, improves accuracy, and supports data-driven decision-making in rural infrastructure planning.

The model is developed and deployed using **IBM Cloud Lite services**, leveraging **IBM Watsonx.ai Studio** and **AutoAI**.

---

## ❓ Problem Statement
PMGSY comprises multiple schemes, including PMGSY-I and PMGSY-II, each with distinct objectives and funding structures. Manually classifying thousands of infrastructure projects into the correct scheme is time-consuming, error-prone, and inefficient, affecting project monitoring and fund allocation.

---

## 💡 Proposed Solution
A supervised machine learning model is trained on historical PMGSY project data using physical and financial attributes. Once deployed, the model automatically predicts the correct PMGSY scheme for new projects and provides a confidence score for each prediction.

---

## 🛠️ Technologies Used
- IBM Cloud Lite  
- IBM Watsonx.ai Studio  
- IBM AutoAI  
- IBM Watson Machine Learning  
- Machine Learning (Multiclass Classification)  
- XGBoost Classifier  

---

## 📊 Dataset
- **Source:** AI Kosh – PMGSY Dataset  
- **Features:** Road length, sanctioned cost, central/state share, year of sanction, etc.  
- **Target Variable:** `PMGSY_SCHEME`

---

## ⚙️ Model Workflow
1. Dataset uploaded to IBM Cloud Object Storage  
2. Data preprocessing and feature engineering using AutoAI  
3. Model training and evaluation with multiple pipelines  
4. Best-performing model selected and deployed  
5. Predictions tested using sample project inputs  

---

## ✅ Results
The deployed model successfully classifies PMGSY projects with high confidence scores, demonstrating reliable and accurate performance.

---

## 🌐 Domain
Artificial Intelligence & Machine Learning  
(Smart Governance / Public Infrastructure Management)

---

## 🚀 Future Scope
- Inclusion of additional PMGSY schemes  
- Integration of GIS-based features  
- Explainable AI for transparency  
- Real-time monitoring dashboards  

---

## 👤 Author
**Dyutishmaan Das**  
Haridwar University – B.Tech CSE with AI & ML
