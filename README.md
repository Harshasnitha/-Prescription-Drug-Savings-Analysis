# Prescription Drug Savings Analysis
# 💊 Drug Prescription Prediction using Decision Tree Classifier

## 📌 Project Description
This project demonstrates how a **Decision Tree Classifier** can be used to predict the most suitable **drug prescription** based on patient data. Using key features like **age**, **sex**, **blood pressure**, **cholesterol**, and **sodium-to-potassium ratio**, the model learns to recommend one of several drugs.

The project covers the full machine learning workflow — from **data preprocessing** and **training** to **evaluation** and **visualization** — using Python and libraries such as **Scikit-learn**, **NumPy**, **Pandas**, and **Matplotlib**.

---

## 📁 Dataset

- **Source**: [Kaggle / IBM ML Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%203/data/drug200.csv)
- **Features**:
  - `Age`: Age of the patient
  - `Sex`: Gender (M/F)
  - `BP`: Blood Pressure level (LOW, NORMAL, HIGH)
  - `Cholesterol`: Cholesterol level (NORMAL, HIGH)
  - `Na_to_K`: Sodium to Potassium ratio
  - `Drug`: Prescribed drug (target variable)

---

## ⚙️ Technologies Used

| Tool/Library    | Purpose                          |
|----------------|----------------------------------|
| Python          | Programming language             |
| Pandas          | Data handling and manipulation   |
| NumPy           | Numerical operations             |
| Scikit-learn    | Machine Learning model & metrics |
| Matplotlib      | Data visualization               |

---

## 🧪 Workflow Summary

1. **Data Loading**: Load CSV from URL using `pandas`.
2. **Preprocessing**:
   - Label encode categorical variables (`Sex`, `BP`, `Cholesterol`).
3. **Train/Test Split**:
   - Use `train_test_split` (70% train, 30% test).
4. **Model Training**:
   - Train `DecisionTreeClassifier` with `criterion='entropy'` and `max_depth=4`.
5. **Prediction & Evaluation**:
   - Predict test labels and print accuracy.
6. **Visualization**:
   - Display decision tree using `plot_tree`.

---

## ✅ Output

- Model Accuracy: (Printed via `metrics.accuracy_score`)
- Sample Predictions:


