# Fraud Analysis Report

## 📊 Project Overview
This project performs a fraud detection analysis on transaction data, focusing on identifying the top regions with the highest fraud transaction volumes and applying machine learning models to predict fraudulent activities.

## 📝 Notebook Highlights
- **Data Loading & Preprocessing:**
    - Merged multiple datasets including user, card, transaction, and merchant information.
    - Cleaned and prepared the data for analysis.

- **Exploratory Data Analysis (EDA):**
    - Identified **Top 3 U.S. States** with the highest number of fraudulent transactions: **Ohio, California, and Texas**.
    - Performed in-depth transaction analysis per state.

- **Modeling Fraud Detection:**
    - Built **XGBoost classification models** specifically for the top three states.
    - Evaluated models using common classification metrics (accuracy, recall, F1-score).

- **Key Observations:**
    - Focused on demographic features (age, gender), transaction amount, and region-based segmentation.
    - XGBoost model demonstrated high performance in fraud classification tasks.

## 🛠️ Tools and Libraries Used
- Python (pandas, numpy, matplotlib, seaborn)
- Machine Learning: scikit-learn, XGBoost
- Visualization: matplotlib, seaborn


## ⚠️ Notes
- The notebook processes multiple datasets including users, cards, transactions, and merchant category codes (MCC).
- This project focuses specifically on three U.S. states with the highest reported fraud activity.
- Dataset files are not included and should be prepared according to the data loading sections in the notebook.

## 💡 Objectives
✅ Identify high-fraud regions  
✅ Conduct exploratory data analysis (EDA)  
✅ Build machine learning models for fraud detection  
✅ Evaluate model performance on selected regions


