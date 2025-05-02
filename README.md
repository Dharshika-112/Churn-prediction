
 📊 Customer Churn Prediction

This project is a complete machine learning pipeline for predicting customer churn using multiple classification models. It includes data preprocessing, feature engineering, model training, evaluation, and saving the best model.

---
 🔍 Problem Statement

Customer churn is a major challenge in many industries. The goal of this project is to predict whether a customer will churn (leave) based on historical data. Accurate prediction allows companies to take proactive actions to retain valuable customers.

---

📁 Project Structure

```

customer-churn-prediction/
│
├── churn\_model.py               # Main Python script to train and evaluate models
├── exploratory\_analysis.ipynb   # Jupyter notebook for EDA (Exploratory Data Analysis)
├── data/
│   └── customer\_churn\_prediction\_dataset.csv
├── best\_churn\_model.pkl         # Trained model saved with joblib
├── requirements.txt             # List of Python dependencies
└── README.md                    # Project documentation

````

---

🚀 How to Run

 1. Clone the repository
bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

 2. Install dependencies

bash
pip install -r requirements.txt

3. Add your dataset

Place your dataset file as `data/customer_churn_prediction_dataset.csv`.

 4. Run the model

bash
python churn_model.py


 📦 Dependencies

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* imbalanced-learn
* xgboost
* lightgbm
* catboost
* joblib

Install with:

bash
pip install -r requirements.txt


 🧠 Models Used

* Logistic Regression
* Random Forest
* Gradient Boosting
* AdaBoost
* Support Vector Machine (SVM)
* Naive Bayes
* K-Nearest Neighbors
* XGBoost
* LightGBM
* CatBoost

Each model is evaluated using:

* Accuracy
* Precision, Recall, F1-Score
* ROC-AUC
* Cross-validation


 🛠 Features

* SMOTE for class imbalance handling
* Preprocessing pipeline with one-hot encoding and scaling
* Cross-validation for model robustness
* Automatic best model saving
* Optional hyperparameter tuning via GridSearchCV


📈 Results

Models are compared using ROC-AUC. The best-performing model is saved as `best_churn_model.pkl`.


 ✅ Author

Developed by \[Your Name]
GitHub: [github.com/your-username](https://github.com/Dharshika-112)


 📜 License

This project is open-source and available under the MIT License.

