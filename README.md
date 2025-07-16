# Fraud Detection Using Mobile Money Transactions (PaySim Dataset)

This project focuses on identifying fraudulent mobile money transactions using the **PaySim** dataset, a realistic simulation based on logs from a financial service in Africa. Throughout the project, I applied multiple machine learning models, explored data patterns, and implemented optimization strategies to enhance fraud detection.

---

## Objectives
- Perform in-depth Exploratory Data Analysis (EDA) to uncover transaction patterns
- Build and evaluate various classification models to predict fraud
- Address class imbalance and improve model performance through advanced preprocessing
- Compare and select the best-performing model using multiple evaluation metrics

---

##  Project Highlights

###  Exploratory Analysis
- Distribution analysis of transaction types
- Log-transformation of skewed features like `amount`
- Detection of unusual patterns in sender/receiver balances (Δ balance anomalies)

###  Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Each model was trained and evaluated using both default parameters and tuned configurations.

###  Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC Curve & AUC

Special focus was placed on Precision and F1-Score due to the nature of fraud detection, where minimizing both false positives and false negatives is important. However, my primary focus was on minimizing false negatives to ensure that fraudulent transactions are not missed, which is critical in real-world scenarios.
###  Improvement Techniques
- Addressed **class imbalance** using **random undersampling** and **SMOTE**
- Applied **log transformation** to normalize skewed features
- Feature scaling and encoding of categorical variables

---

Based on cross-validation, **XGBoost** delivered the best trade-off between precision and recall, making it the top choice for deployment in real-world fraud detection systems.

---

##  Future Improvements
- Integrate cost-sensitive learning to penalize fraud misclassifications
- Deploy the final model as a real-time API using Flask or FastAPI
- Test on real-world datasets or synthetic streaming data
- Introduce time-based validation to mimic live transaction flows

---

##  Files
- `BaharDataMiningProject.ipynb`: Full code, EDA, modeling, and results

---

## About Me
I'm Bahar, a data science student with a passion for applying analytics in finance, particularly in fraud detection and transactional analysis. Let’s connect!

 [LinkedIn](www.linkedin.com/in/baharal)

