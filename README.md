# Telecom Customer Data - Exploratory Data Analysis (EDA)

This project performs an in-depth exploratory data analysis (EDA) on a telecom customer dataset to uncover key patterns, clean the data, and visualize customer behaviors and campaign responses.

## 🔍 Project Objectives

- Clean and preprocess raw telecom data
- Handle missing and invalid values
- Visualize key relationships and distributions
- Explore response trends based on job, education, age, and more
- Prepare encoded dataset for future modeling

## 🛠 Tools & Libraries

- Python (Pandas, NumPy)
- DataPrep
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Key Insights

- Certain job roles and education levels showed higher campaign response rates
- Duration of last contact is a strong indicator of success
- Outliers in age and campaign activity were filtered to enhance data quality

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ftme-lyc/telecom-eda.git
   cd telecom-eda
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook:
   Open EDA_project.ipynb in Jupyter Notebook or VS Code
   
## 📁 Files Included

- `EDA_project.ipynb` – The Jupyter notebook containing all EDA steps.
- `eda_project.py` – A script version of the notebook for easier code review.
- `TeleCom_Data.csv` – The original dataset used for analysis.
- `requirements.txt` – List of packages required to run the project.
- `EDA_report.pdf` – Detailed project report summarizing findings and methodology.

________________________

# Marketing Campaign Subscription Prediction

In today’s competitive telecommunications industry, understanding customer behavior and predicting their response to marketing campaigns is critical for success. This project focuses on predicting the likelihood of customers subscribing to a new telecommunication plan using machine learning models.

## Project Overview

By analyzing customer data, the models uncover key patterns that allow for targeted marketing approaches. The best-performing model achieved over 90% accuracy, and the project identified actionable business insights to guide future marketing strategies, optimizing campaign effectiveness and maximizing return on investment.

## Problem Statement

The company faces challenges in identifying customer segments most responsive to marketing campaigns, leading to inefficient strategies and missed opportunities. This project aims to predict customer subscription to a new plan based on historical data, enabling data-driven decision-making and better marketing targeting.

## Methods

### Data Acquisition & Preprocessing

- The dataset includes numerical and categorical features, with a Boolean target variable indicating subscription.
- Data preprocessing involved handling missing values and balancing the dataset using SMOTE to address target class imbalance.

### Models Used

Four machine learning models were developed and evaluated:

1. Logistic Regression  
2. Decision Tree  
3. Multi-layer Perceptron (MLP) Classifier  
4. XGBoost  

- Principal Component Analysis (PCA) was tested, but did not improve model performance.
- Models were evaluated using Accuracy, Precision, Recall, and F1-Score with cross-validation to ensure generalization.
- A Generalized Linear Model (GLM) using Maximum Likelihood Estimation (MLE) was applied to extract key business insights.

## Results

- The **Decision Tree** model outperformed others with accuracy of 98.5%, precision of 98.2%, recall of 98.5%, and F1-Score of 98.3%, making it highly effective at identifying likely subscribers.
- XGBoost showed balanced precision and recall, while Logistic Regression and MLP had slightly lower performance.
- Key predictors identified include consumer price index, duration of contact, contact method, and previous campaign engagement.

## Business Insights

1. **Duration of Contact:** Longer contacts significantly increase subscription likelihood.  
2. **Contact Method:** Certain methods negatively impact outcomes; optimizing communication channels is needed.  
3. **Economic Indicators:**  
   - Lower employment variation rate improves campaign success.  
   - Higher consumer price index correlates with better response rates.  
4. **Previous Campaigns:** Multiple prior contacts can lead to customer fatigue and reduce effectiveness.

These insights can help refine targeting and improve campaign efficiency.

## Conclusion

This project demonstrates the effectiveness of machine learning in predicting customer subscription and supporting marketing strategy optimization. The Decision Tree model is the best performer, providing reliable predictions and valuable insights to improve campaign success, ROI, and customer loyalty.

Future work could explore more features, segment-specific modeling, and real-time data integration for dynamic prediction capabilities, further enhancing marketing precision.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ftme-lyc/telecom-eda.git
   cd telecom-eda
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook:
   Open statistical_project.ipynb in Jupyter Notebook or VS Code

## 📁 Files Included

- statistical_project.ipynb – Jupyter Notebook containing all data analysis and modeling steps.
- statistical_project.py – Script version of the notebook for streamlined code review.
- TeleCom_Data.csv – Original dataset used in the analysis.
- requirements.txt – List of dependencies required to run the project.
- Data analysis project for marketing campaigns.pdf – Comprehensive project report summarizing the methodology, analysis, and key findings.
