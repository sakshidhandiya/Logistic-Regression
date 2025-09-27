# Logistic-Regression
Logistic Regression Model for Small-Scale Manufacturing Analysis
# Supervised Learning on Manufacturing Data
This project demonstrates the application of Logistic Regression, a supervised machine learning technique, on a small manufacturing dataset.
The goal is to classify manufacturing outcomes (Yes/No) based on financial and operational indicators.

The project is implemented in Python using Google Colab, and includes all stages of a typical data science workflow — from data preparation and visualization to model building and evaluation.

## 📊 Dataset
- Features(Independent Variables): Cash Compensation, Sales, Number of Employees, Capital Investment  
- Target (Dependent Variable): Manufacturing (0 = No, 1 = Yes)  
- Size: 22 records (balanced classes)
- Missing Values: None detected in the dataset.

## 🛠️ Methodology
1. Data cleaning & preprocessing  
2. Exploratory Data Analysis (EDA):
    Visualized class distribution of the target variable.

    Computed correlations between features and the target.

    Gained insights into which factors may influence manufacturing outcomes.  
4. Logistic Regression modeling: 
    Defined features (X) and target (y).

    Performed train-test split (70% training, 30% testing).

    Built a Logistic Regression model using Scikit-learn.  
5. Model evaluation: 
    Confusion Matrix

    Classification Report (Precision, Recall, F1-score)

    ROC-AUC Score

    Analyzed model coefficients to interpret feature importance.  

## ✅ Results
- Accuracy: **100% (on test set, small sample)**  
- AUC: **1.0**  
- Feature Importance (Coefficients):

    Capital Investment → Positive influence (+0.361)

    Number of Employees → Slight positive influence (+0.083)

    Cash Compensation → Slight negative influence (-0.025)

    Sales → Negative influence (-0.628)

## ⚙️ Tools & Libraries
- Python (Google Colab)  
- Libraries:

    pandas – data manipulation

    numpy – numerical computations

    matplotlib, seaborn – data visualization

    scikit-learn – model building & evaluation

    statsmodels – statistical analysis
