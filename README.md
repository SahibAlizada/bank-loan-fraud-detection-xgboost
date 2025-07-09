# Bank Loan Fraud Detection using XGBoost

This project focuses on detecting fraudulent activities in bank loan transactions using machine learning, specifically the XGBoost classifier.

## 📌 Objective
To identify whether a bank loan transaction is fraudulent based on various input features such as loan amount, transaction type, customer profile, and more.

## 📁 Dataset
The dataset includes:
- Customer transaction details
- Device and GPU information
- Transaction amounts
- Flags and fraud labels (target variable)

## ⚙️ Project Workflow
1. **Data Cleaning & Preprocessing**  
   - Handled missing values  
   - Converted categorical columns into numerical (label encoding, one-hot encoding)

2. **Feature Engineering**  
   - Created new features from existing columns (e.g. time-based patterns, device usage)

3. **Model Building**  
   - XGBoost Classifier was used due to its high performance and interpretability  
   - Hyperparameter tuning performed for optimal results

4. **Evaluation Metrics**  
   - Accuracy  
   - Confusion Matrix  
   - Precision, Recall, F1-Score  
   - ROC-AUC

5. **Visualization**  
   - Feature importance plot  
   - Fraud distribution  
   - Correlation heatmaps

## 🎯 Results
- Model Accuracy: **~73%**
- The most important features influencing fraud detection were: `MaritalStatus`, `Collateral`, `InterestRate`, `DeviceInformation`,`SocialMediaFootprint`,`LoanAmountRequested`

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Google Colab

## 📂 File Structure

