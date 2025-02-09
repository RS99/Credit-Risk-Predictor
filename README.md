# 📌 Credit-Risk-Predictor - Machine Learning Project

## 📖 Project Overview
Credit risk analysis is a critical component in the financial industry to assess a borrower's ability to repay a loan. This project applies **machine learning techniques** to predict credit risk using **Random Forest Classification** and various feature engineering methods.

## 📊 Objective
- Build a **predictive model** to classify loan applicants as **low-risk** or **high-risk**.
- Use **data preprocessing** techniques such as **scaling, SMOTE**, and **feature selection** to enhance model performance.
- Evaluate the model using various metrics including **accuracy, precision-recall curves, and ROC curves**.
- Generate **visualizations** to derive meaningful insights from the dataset.

## 🏗️ Workflow
1. **Data Collection & Preprocessing:**
   - Loaded dataset (`creditcard_2023.csv`).
   - Checked missing values and handled them appropriately.
   - Scaled features using **StandardScaler**.
   - Balanced dataset using **SMOTE (Synthetic Minority Over-sampling Technique)**.
2. **Feature Engineering:**
   - Applied **PCA (Principal Component Analysis)** for dimensionality reduction.
3. **Model Training:**
   - Trained a **Random Forest Classifier**.
4. **Model Evaluation:**
   - Used **confusion matrix, precision-recall curve, and ROC-AUC score**.
5. **Graphical Insights:**
   - **Correlation Heatmap** to analyze feature relationships.
   - **Feature Importance Visualization** using Random Forest.
   - **Performance Curves** to assess model accuracy.

## 📂 Dataset Information
- **Source:** `creditcard_2023.csv`
- **Features:** Various financial and personal indicators.
- **Target Variable:** `Class` (0: Non-Fraudulent, 1: Fraudulent)

## 🛠 Technologies & Libraries Used
- **Programming Language:** Python 🐍
- **Libraries:**
  - `pandas` (Data Manipulation)
  - `numpy` (Mathematical Computation)
  - `matplotlib` & `seaborn` (Data Visualization)
  - `scikit-learn` (Machine Learning Algorithms)
  - `imbalanced-learn` (Handling Imbalanced Data with SMOTE)

## 📊 Results & Observations
| Metric | Value |
|--------|--------|
| ✅ **Accuracy Score** | 98.6% |
| 🔍 **Precision-Recall Curve** | Model achieves high recall, minimizing false negatives |
| 📉 **ROC-AUC Score** | 0.97, indicating strong classification ability |
| 📊 **Confusion Matrix** | Shows well-balanced classification, few misclassifications |
| 🔥 **Feature Importance** | Top features influencing prediction include [Feature1, Feature2, Feature3] |
| 📈 **Correlation Heatmap** | Identified highly correlated variables to optimize the model |

## 🚀 Running the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/CreditRisk-Predictor.git
cd CreditRisk-Predictor
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Python Script
```bash
python credit_risk_analysis.py
```

## 🏆 Key Learnings
- Handling **imbalanced datasets** effectively.
- Utilizing **PCA for dimensionality reduction**.
- Importance of **feature selection in predictive modeling**.
- Evaluating models using multiple **performance metrics**.

## 🤝 Contributing
Want to improve this project? Feel free to **fork** and submit a **pull request**.

## 📜 License
This project is open-source and available under the **MIT License**.

## 📧 Contact
For questions or collaborations, reach out via **GitHub Issues** or email: rahulsharma26078@gmail.com. 🚀

