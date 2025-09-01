# bank-marketing-classification
Statistical analysis and ML pipeline to predict customer subscription in a bank marketing campaign.

## 📌 Business Context
The dataset comes from a Portuguese bank’s telemarketing campaign. The goal is to predict whether a customer will subscribe to a term deposit (`yes` or `no`) after being contacted. This helps banks improve campaign efficiency and focus on the right customers.

## 📊 Tools & Techniques Used
- **Statistics** → To understand data distribution, correlation, and hypothesis testing  
- **EDA (Exploratory Data Analysis)** → Univariate, Bivariate, and Multivariate analysis  
- **Feature Engineering & Preprocessing** → Encoding categorical features, handling missing values, scaling  
- **Machine Learning Models** → Logistic Regression, Decision Tree, Random Forest, etc.  
- **Model Evaluation** → Accuracy, Precision, Recall, F1-score  

## 📂 Project Workflow
1. **Data Understanding** – Examined dataset shape, columns, and business meaning  
2. **Exploratory Data Analysis (EDA)** – Identified key patterns & customer behavior  
3. **Data Preprocessing** – Encoding, scaling, handling imbalanced data  
4. **Model Building** – Built ML models for classification  
5. **Model Selection** – Compared models, selected Logistic Regression for best balance of performance & interpretability  
6. **Deployment** (optional) – Prepared model for deployment with Streamlit  

## 📈 Key Insights
- Most customers do not subscribe (~88% ‘no’, 12% ‘yes’) → highly imbalanced dataset  
- Age, job type, and contact duration strongly influence subscription likelihood  
- Logistic Regression performed best with Recall as the business-focused metric  

## ⚙️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- Jupyter Notebook  
- Streamlit (for deployment, optional)  

## 📎 Dataset
- **Source**: UCI Machine Learning Repository - Bank Marketing Dataset  

---
