# 🚀 Credit Card Fraud Detection
This project detects fraudulent credit card transactions using machine learning.
## 📌 Task Objectives
- Identify fraudulent transactions from a dataset.
- Handle class imbalance using **SMOTE**.
- Train and evaluate machine learning models (**XGBoost & Random Forest**).

## 📂 Dataset
- The dataset is from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
- It contains 284,807 transactions, with only 492 fraud cases (highly imbalanced).
## 🔧 Steps to Run the Project
1. **Open Google Colab**  
   - Go to [Google Colab](https://colab.research.google.com/).  
2. **Upload the dataset (`creditcard.csv`)**.  
3. **Run the code cells in order** to preprocess data, train models, and evaluate.  
4. **Install required libraries** using:  
   ```python
   !pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn xgboost
5.Train the models (XGBoost & Random Forest) and evaluate results.
📊 Model Evaluation
XGBoost Recall: 88% (preferred for fraud detection)
Random Forest Precision: 87% (balanced approach)
Final Model: XGBoost (saved as fraud_detection_model.pkl)
🛠️ Technologies Used
Python
Google Colab
Pandas, NumPy
Scikit-learn, imbalanced-learn
Seaborn, Matplotlib
