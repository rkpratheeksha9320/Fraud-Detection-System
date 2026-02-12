## Fraud Detection System using Machine Learning

## Project Objective
The objective of this project is to detect fraudulent financial transactions using Machine Learning classification models. The system includes data preprocessing, model training, prediction generation, and interactive dashboard visualization.

This project demonstrates an end-to-end fraud detection pipeline from raw dataset to business intelligence reporting.

---

## Technologies Used
- Python
- Pandas & NumPy
- Scikit-Learn
- Machine Learning Classification Models
- Joblib (Model Saving & Loading)
- Jupyter Notebook
- Power BI

---

## Project Structure

Fraud-Detection-System/
│
├── dashboard/ # Power BI Dashboard (.pbix)
├── data/ # Raw dataset (.csv)
├── notebook/
│ └── fraud_model_training.ipynb # Model training & evaluation
├── model/
│ └── fraud_model.pkl # Saved ML model (Joblib)
├── output/
│ ├── fraud_prediction.csv # Generated predictions
│ └── fraud_dashboard_dataset.csv 
└── README.md


---

## Project Workflow

### 1️⃣ Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Performed feature engineering
- Prepared training and testing datasets

### 2️⃣ Model Training
- Trained Machine Learning classification models
- Evaluated model performance using accuracy and classification metrics

### 3️⃣ Model Saving
- Saved the trained model using Joblib (.pkl file)

### 4️⃣ Prediction Generation
- Generated fraud prediction output file
- Prepared encoded dataset for Power BI visualization

### 5️⃣ Dashboard Development
Developed a multi-page interactive Power BI dashboard covering:

- *Overview* – Key fraud KPIs and summary metrics  
- *Location & Merchant Risk* – High-risk geographic and merchant analysis  
- *Device, Card & Transaction Analysis* – Fraud distribution by device, card type, and transaction category  
- *Fraud Alerts* – Identification of high-risk transactions  
- *Trend Analysis* – Time-based fraud patterns  
- *User Risk Profiling* – User-level fraud risk assessment  
- *Account Balance Analysis* – Fraud trends by balance and transaction amount  
- *Behavioral Analysis* – Historical fraud behavior insights  
- *Card & Age Analysis* – Fraud risk based on card type and card age  

The dashboard includes interactive slicers and dynamic filtering for detailed fraud investigation.
---

## Key Results
- Built a structured multi-page fraud analytics dashboard
- Identified high-risk users, locations, and transaction categories
- Successfully classified fraudulent transactions using ML models
- Integrated machine learning predictions with business intelligence reporting


---

## Conclusion
This project demonstrates a complete Machine Learning lifecycle:
- Data preprocessing
- Model training & evaluation
- Model saving (Joblib)
- Prediction generation
- Business Intelligence dashboard integration

It reflects practical implementation of Data Science in financial fraud detection.

---
## 📸 Dashboard Preview

![Overview](dashboard_screenshot/dashboard1.png)

![Location and merchant risk](dashboard_screenshot/dashboard2.png)

![Device and transaction type Analysis](dashboard_screenshot/dashboard3.png)
