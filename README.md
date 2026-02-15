# Term Deposit Subscription Prediction

## Objective

The goal of this project is to predict whether a bank customer will subscribe to a term deposit based on demographic, financial, and marketing campaign information.

This helps financial institutions target potential customers more effectively and reduce unnecessary marketing costs.

---

## Dataset

**Bank Marketing Dataset (UCI Repository)**

The dataset contains customer information such as:

* Age
* Job
* Marital status
* Education
* Account balance
* Previous campaign interactions
* Contact duration

Target Variable:

* `y` → yes (subscribed) / no (not subscribed)

---

## Approach

### 1. Data Preprocessing

* Encoded target variable into binary values
* Applied One-Hot Encoding for categorical features
* Performed stratified train-test split

### 2. Models Used

* Logistic Regression
* Random Forest Classifier

### 3. Model Evaluation

Models were evaluated using:

* Confusion Matrix
* Precision, Recall, F1-Score
* ROC-AUC Score

Random Forest showed superior performance.

---

## Explainable AI (XAI)

Five individual predictions were explained using SHAP/LIME to interpret feature contributions.

Key Influential Features:

* Call duration
* Account balance
* Age
* Campaign contacts
* Previous contact days

---

## Results

The Random Forest model achieved strong predictive performance and demonstrated reliable customer targeting capability.

---

## Conclusion

Machine learning can effectively predict customer subscription behavior and help banks design efficient marketing strategies.

---

## Repository Structure

* notebook.ipynb
* shap_prediction_*.png
* README.md
