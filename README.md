# Customer Churn Prediction 📊

## Project Overview
This project predicts which customers are likely to churn (cancel their service) using machine learning. Built with Python, this model helps businesses identify at-risk customers before they leave.

## 🎯 Key Results
| Metric | Score |
|--------|-------|
| **ROC-AUC** | 0.8422 |
| **Accuracy** | 80.7% |
| **Precision** | 66.0% |
| **Recall** | 56.1% |
| **F1-Score** | 60.7% |

## 📊 Dataset
- **Source:** Telco Customer Churn (Kaggle)
- **Size:** 7,043 customers
- **Features:** 21 (demographics, account info, services)
- **Target:** Churn (Yes/No)

## 🔍 Key Insights Discovered
1. **Contract Type:** Month-to-month customers churn at 42% vs 3% for 2-year contracts
2. **First 6 Months:** 47% of churn happens in first 6 months
3. **Payment Method:** Electronic check users churn at 45% vs 15% for auto-pay
4. **Monthly Charges:** $60-90 group has highest churn (33.9%)
5. **Services:** Customers without online security and tech support churn more

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- SMOTE (for class imbalance)

## 📁 Project Structure