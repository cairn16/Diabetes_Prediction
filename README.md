# 🩺 Diabetes Prediction and Analysis Project

This project explores and predicts the likelihood of diabetes in individuals using a publicly available dataset. It includes a comprehensive **Power BI dashboard**, **machine learning models**, and **feature importance analysis** to better understand diabetes indicators.

---

## 📂 Project Structure

- **Dataset:** `diabetes_prediction_dataset.csv`
- **Notebook:** Python (Google Colab/Jupyter compatible)
- **Dashboard:** Power BI report file
- **Outputs:** Performance metrics, feature analysis, and visualizations
- **Models Used:** Logistic Regression, Random Forest, XGBoost

---

## 📊 Dashboard Overview

### Key Visuals:

- Diabetes Prevalence by Age and Gender  
- Average BMI, Glucose, HbA1c across categories  
- Feature importance from models  
- Cards showing total records, positive cases, average values

---

## ⚙️ Model Performance

### ✅ Logistic Regression
- **Accuracy:** 96.03%  
- **Precision (0/1):** 0.97 / 0.86  
- **Recall (0/1):** 0.99 / 0.64  
- **F1-score (0/1):** 0.98 / 0.73  

### ✅ Random Forest
- **Accuracy:** 97.03%  
- **Precision (0/1):** 0.97 / 0.95  
- **Recall (0/1):** 1.00 / 0.69  
- **F1-score (0/1):** 0.98 / 0.80  

### ✅ XGBoost
- **Accuracy:** 97.10%  
- **Precision (0/1):** 0.97 / 0.94  
- **Recall (0/1):** 1.00 / 0.70  
- **F1-score (0/1):** 0.98 / 0.80  

> The models performed exceptionally well, with XGBoost showing the highest accuracy and balanced precision/recall scores.

---

## 🔍 Feature Importance Highlights

Most impactful features:
- HbA1c Level  
- Blood Glucose Level  
- BMI  
- Age  
- Hypertension  

---

## 🛠️ Technologies Used

- **Python**: pandas, scikit-learn, xgboost, seaborn, matplotlib  
- **Google Colab**: for development  
- **Power BI**: for interactive dashboard  
- **GitHub**: version control and hosting  

---

## 💾 Dataset

- **File**: `diabetes_prediction_dataset.csv`  
- **Source**: [Kaggle - Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)

---

## 💡 How to Run

1. Clone this repository  
2. Open `diabetes_analysis.ipynb` in Colab or Jupyter  
3. Upload the dataset and run all cells  
4. Open `.pbix` dashboard file in Power BI Desktop  

---

## 👥 Contributors

- **Cairn Correia**   
  🔗 [LinkedIn: Shorn Correia](https://www.linkedin.com/in/cairn-correia)
  cairncorreia@gmail.com

- **Shorn Correia**   
  🔗 [LinkedIn: Shorn Correia](https://www.linkedin.com/in/shorn-correia)
  shorncorreia@gmail.com

---

## 📃 License

This project is intended for educational and research purposes only.
