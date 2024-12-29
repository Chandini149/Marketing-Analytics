# Predictive Marketing Analytics: Statistical Insights for Business Success

📈 **Project Overview**  
This project applies advanced statistical learning techniques to predict customer subscription patterns for term deposits. Using the 'Marketing_data.csv' dataset, predictive models were developed to refine marketing strategies in the financial sector.

📊 **Key Features**  

**📂 Dataset:**  
- **Source**: Inspired by the UCI Machine Learning Repository (bank.csv).  
- **Content**: 11,162 observations and 17 features, including demographic, financial, and campaign-specific attributes.  
- **Target**: Binary classification of the `deposit` variable ('yes' or 'no').

**⚙️ Data Preprocessing:**  
- Feature engineering:
  - Created `age_group` and `month_part` features.  
  - Interaction effects between `pdays` and `duration`.  
- Converted categorical variables to factors.  
- Standardized numerical variables.  

**🔎 Exploratory Data Analysis (EDA):**  
- Visualized distributions and relationships.  
- Correlation and chi-square tests identified influential predictors.  

**🎯 Feature Selection:**  
- Logistic Lasso regression and Random Forest importance analysis highlighted key features:  
  - **Top Predictors**: Duration, month, age group, balance, housing, and previous campaign outcomes.

🛠️ **Methodology**  
1. **🧠 Statistical Learning Models**:
   - 🌲 Random Forest  
   - 📊 Logistic Regression  
   - 🌀 Support Vector Machines (SVM)  
   - 🌴 Decision Trees  

2. **📋 Evaluation Metrics**:  
   - Accuracy, Precision, Recall, F1-Score, ROC-AUC.  
   - Resampling techniques (bootstrapping and 5-fold cross-validation).  

📉 **Results**  
**Model Performance on Test Data**:  
| Model               | 🏆 Accuracy | 🎯 Precision | 🔁 Recall | 📊 F1-Score | 📈 ROC-AUC |
|---------------------|-------------|--------------|-----------|-------------|------------|
| 🌲 Random Forest    | 85.76%      | 89.88%       | 82.03%    | 85.77%      | 91.91%     |
| 📊 Logistic Regression | 82.17%   | 81.45%       | 85.40%    | 83.38%      | 90.31%     |
| 🌀 SVM              | 83.67%      | 85.39%       | 83.02%    | 84.18%      | 91.11%     |
| 🌴 Decision Tree    | 80.95%      | 81.02%       | 83.06%    | 82.03%      | 83.82%     |

**💡 Key Insights:**  
- 🌲 Random Forest achieved the highest accuracy and F1-score, demonstrating superior predictive power.  
- 📊 Logistic Regression and 🌀 SVM offered competitive performance, balancing precision and recall.  
- 🌴 Decision Trees provided interpretable results with robust performance.  

🚀 **Future Work**  
- 🌐 Integrate additional data sources (e.g., socioeconomic indicators).  
- 🤖 Explore ensemble models and deep learning architectures.  
- ⚖️ Address dataset biases and enhance feature engineering.
