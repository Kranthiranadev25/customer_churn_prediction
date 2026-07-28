# Customer Churn Prediction

A machine learning project designed to predict user churn risk and identify key drivers behind customer attrition.

##  Project Overview
Customer churn occurs when customers stop doing business with a company. This project builds a predictive model to identify high-risk customers, allowing businesses to implement proactive retention strategies.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / VS Code

## 📁 Project Structure
```text
├── data/               # Raw and processed datasets
├── notebooks/          # Exploratory Data Analysis (EDA) & modeling
├── src/                # Source code for pipeline and scripts
├── README.md           # Project documentation
└── requirements.txt    # List of dependencies
```

## ⚙️ Workflow Steps

### 1. Data Preprocessing
- Handled missing values and removed duplicates.
- Encoded categorical variables (e.g., One-Hot Encoding).
- Scaled numerical features using standard scaling.

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution across demographics.
- Investigated correlations between account tenure, contract types, charges, and churn.

### 3. Model Training & Evaluation
- Split data into training and testing sets (80/20 split).
- Trained multiple classifiers (e.g., Logistic Regression, Random Forest, XGBoost).
- Evaluated performance using Accuracy, Precision, Recall, and F1-Score.

## 🚀 Results & Performance
*Note: Replace the placeholder values below with your final model metrics.*


| Model Name | Accuracy | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| Logistic Regression | 0.00% | 0.00 | 0.00 | 0.00 |
| Random Forest | 0.00% | 0.00 | 0.00 | 0.00 |
| XGBoost (Best) | **0.00%** | **0.00** | **0.00** | **0.00** |

### Key Insights
- **Feature Importance:** [Insert top feature, e.g., Tenure or Contract Type] was the strongest predictor of churn.
- **Business Impact:** The final model successfully catches [00]% of churning customers before they leave.

