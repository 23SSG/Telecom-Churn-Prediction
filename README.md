
# 📊 Telecom Customer Churn Prediction Using Machine Learning

### 🚀 Project Overview

Customer churn is one of the biggest challenges in the Indian telecom industry, where intense competition and easy number portability make customer retention difficult. This project leverages **machine learning** to predict customer churn and uncover **key behavioral and demographic drivers** behind customer attrition.

By analyzing real-world telecom data, this project demonstrates how **data science can directly support business decisions**, improve customer retention strategies, and reduce revenue loss.

### 🎯 Business Problem

Telecom companies lose significant revenue when customers leave for competitors.
**Key business questions addressed in this project:**

* Which customers are most likely to churn?
* What factors contribute most to churn?
* How can telecom providers proactively retain high-risk customers?

### ⚡ Key Drivers of Customer Churn

Based on industry knowledge and data analysis, major churn drivers include:

* Poor network quality (call drops, low data speed)
* High or unclear pricing plans
* Ineffective customer support
* Lack of personalized offers
* Competitive discounts and promotions
* Easy number portability
* Low service usage or inactivity
* Customer relocation affecting network coverage
* Slow adoption of new technologies (e.g., 5G)
* Weak customer retention strategies

### 📂 Dataset

This project uses two structured datasets representing Indian telecom customers from **Airtel, Reliance Jio, Vodafone, and BSNL**.

* **`telecom_demographics.csv`**

  * Customer demographic attributes (age group, region, customer profile)

* **`telecom_usage.csv`**

  * Service usage metrics (call behavior, data usage, plan details)

These datasets were merged and preprocessed to create a unified analytical view.


### 🧠 Approach & Methodology

1. **Data Cleaning & Preprocessing**

   * Encoding categorical variables
   * Feature scaling and transformation

2. **Feature Engineering**

   * Creating meaningful predictors from raw telecom data

3. **Model Development**

   * Machine learning classifiers such as **Random Forest** and **Logistic Regression**
   * Focus on both **prediction accuracy** and **model interpretability**

4. **Model Evaluation**

   * Accuracy, precision, recall, F1-score
   * Feature importance analysis to explain churn drivers


### 📈 Key Insights & Results

* Machine learning models successfully identified **high-risk churn customers**.
* **Usage patterns, pincode,estimated_salaray,sms_sent,calls_made** were among the strongest predictors of churn.
* Random Forest models provided valuable **feature importance insights**, enabling data-driven retention strategies.
* The project highlights how predictive analytics can move telecom companies from **reactive to proactive customer retention**.

### 🛠️ Tech Stack & Skills Demonstrated

**Languages & Libraries**

* Python, Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

**Data Science Skills**

* Data preprocessing & EDA
* Feature engineering
* Machine learning modeling
* Model evaluation & interpretation
* Business-oriented data storytelling


### 💡 Business Impact

This project demonstrates how telecom companies can:

* Reduce customer churn through early risk detection
* Design personalized retention campaigns
* Improve service quality based on data-driven insights
* Increase customer lifetime value (CLV)


### 📌 Why This Project Matters

This project showcases my ability as a **data scientist / data analyst** to:

* Translate raw data into actionable business insights
* Build interpretable machine learning models
* Communicate results in a business-friendly manner
* Work on real-world, industry-relevant problems


### 📎 Future Enhancements

* Hyperparameter tuning and model optimization
* Implementation of advanced models (XGBoost, LightGBM)
* Time-based churn prediction
* Deployment as a churn prediction dashboard

### 📁 Repository Structure
telecom-churn-prediction/
│
├── data/
│   └── raw/
│       ├── telecom_demographics.csv
│       └── telecom_usage.csv
│
├── notebooks/
│   └── telecom_churn_prediction.ipynb
│
├── README.md
└── .gitignore


