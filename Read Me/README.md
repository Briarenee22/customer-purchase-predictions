
# 🛍️ Customer Purchase Prediction

This project uses machine learning to predict whether a customer will make a purchase based on behavioral and demographic features.

## 📌 Objective
Build a classification model that predicts customer purchase status to support marketing and business strategy efforts.

## 🔍 Workflow
- Data Loading and Initial Exploration
- Exploratory Data Analysis (EDA) and Visualization
- Outlier Handling using 1st and 99th percentile capping
- Feature Scaling with StandardScaler
- Model Building: Logistic Regression, Decision Tree, Random Forest
- Evaluation using Accuracy, Precision, Recall, F1-score
- Feature Importance Analysis with Random Forest

## 📊 Model Comparison

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 84%      |
| Decision Tree      | 90%      |
| Random Forest      | **95.7%** ✅ Best

## 🔍 Key Insights
- **TimeSpentOnWebsite** is the most important feature influencing customer purchases.
- Other top features: Age, AnnualIncome, DiscountsAvailed

## 📁 Included Files
- `Customer_Purchase.ipynb` — Full Jupyter notebook with code and output
- `Customer_Purchase_Prediction_Summary_GitHub.docx` — Clean, structured summary of the project

## 💡 Why This Matters
Understanding customer behavior helps businesses tailor their marketing efforts and improve sales performance. This project provides a reproducible pipeline and clear insights to support such initiatives.

---

📌 Built for learning, sharing, and showcasing end-to-end data science capabilities.
