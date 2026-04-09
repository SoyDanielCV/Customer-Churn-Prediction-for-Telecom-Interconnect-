# 📊 Customer Churn Prediction for Telecom (Interconnect)

## 📌 Business Problem
Customer churn is a major challenge in the telecommunications industry. Retaining existing customers is often more cost-effective than acquiring new ones.

This project aims to build a machine learning model capable of predicting which customers are likely to cancel their service, enabling proactive retention strategies.

---

## 📂 Dataset
The dataset consists of multiple sources containing customer information:

- Contract details
- Personal information
- Internet services
- Phone services

These datasets were merged into a single analytical dataset using a unique customer ID.

---

## ⚙️ Methodology

### 1. Data Preparation
- Merged multiple datasets into a unified structure
- Handled missing values and inconsistent entries
- Created the target variable **Churn**
- Encoded categorical variables using Label Encoding
- Scaled numerical features using StandardScaler

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of numerical and categorical variables
- Identified patterns related to churn behavior
- Evaluated correlations between features

### 3. Model Training
Trained and compared multiple models:
- Logistic Regression
- Random Forest
- XGBoost

### 4. Model Evaluation
Models were evaluated using:
- AUC-ROC
- Accuracy

---

## 📈 Results

| Model               | AUC-ROC | Accuracy |
|--------------------|--------|----------|
| Logistic Regression| 0.8255 | 0.7260   |
| Random Forest      | 0.8588 | 0.7857   |
| XGBoost (Final)    | **0.9013** | **0.8602** |

✅ XGBoost achieved the best performance and was selected as the final model.

---

## 💡 Key Insights
- Customers with monthly contracts are more likely to churn
- Certain payment methods are associated with higher churn rates
- Service combinations (internet + add-ons) influence retention

---

## 🚀 Business Impact
This model enables the company to:
- Identify high-risk customers early
- Implement targeted retention strategies
- Reduce churn and increase customer lifetime value

---

## 🛠️ Tech Stack
- Python
- Pandas / NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn

---

## ▶️ How to Run
(Content in Spanish)
1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells
