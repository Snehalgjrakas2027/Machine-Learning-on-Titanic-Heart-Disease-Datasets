# 🚀 Machine Learning on Titanic & Heart Disease Datasets

This project demonstrates the end-to-end process of preparing and training machine learning models on two popular classification datasets: **Titanic Survival** and **Heart Disease Prediction**. Both datasets go through **data cleaning**, **preprocessing**, **exploratory data analysis**, and are used to train and evaluate **classification algorithms**.

---

## 📊 Datasets Used

### 🛳 Titanic Dataset
- Predicts survival of passengers on the Titanic.
- Features include age, sex, class, family relations, fare, etc.

### ❤️ Heart Disease Dataset
- Predicts whether a person is likely to develop heart disease.
- Features include cholesterol level, resting BP, age, sex, exercise-induced angina, etc.

---

## ⚙️ Preprocessing Techniques Applied

For **both datasets**, the following preprocessing steps were applied:

### ✅ 1. Handling Missing Values
- Titanic: Imputed missing values in `Age` and `Embarked` columns using **mean** and **mode** respectively.
- Heart: Verified dataset integrity (mostly clean).

### ✅ 2. Encoding Categorical Features
- Used **Label Encoding** and **One-Hot Encoding** for features like `Sex`, `Embarked`, and `ChestPainType`.

### ✅ 3. Feature Scaling
- Applied **StandardScaler** to normalize numeric features (e.g., `Age`, `Cholesterol`, `Fare`, `BloodPressure`).

### ✅ 4. Outlier Detection & Removal (Optional)
- Used IQR-based filtering or Z-score methods (as exploratory step).

### ✅ 5. Feature Selection
- Removed irrelevant or highly correlated features where applicable.
- Titanic: Dropped `Cabin`, `PassengerId`, `Name`, `Ticket`.
- Heart: Evaluated correlation matrix to select most informative features.

---

## 📈 Modeling & Evaluation

Used the following classification models on **both datasets**:

- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors**
- **Support Vector Machine (SVM)**

### 📊 Evaluation Metrics:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Curve

---

---

## 💡 Key Learnings

- The Titanic dataset is a classic introduction to **binary classification** and handling **categorical variables**.
- The Heart dataset requires understanding of **medical indicators** and benefits from **scaling and feature engineering**.
- Preprocessing plays a crucial role in boosting model accuracy and generalization.

---



