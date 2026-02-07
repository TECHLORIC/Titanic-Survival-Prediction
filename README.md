# Titanic Survival Prediction 🚢

## 📌 Project Overview
This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques.

The model is built using Logistic Regression and trained on the Kaggle Titanic dataset.

---

## 📊 Dataset Information
- Total Records: 891 passengers
- Target Variable: Survived (0 = No, 1 = Yes)
- Features include Age, Sex, Passenger Class, Fare, Family Size, etc.

---

## 🔧 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Project Workflow

1. Data Cleaning
   - Handled missing values in Age and Embarked
   - Dropped Cabin due to excessive missing data

2. Exploratory Data Analysis
   - Analyzed survival trends by gender, age, and passenger class

3. Feature Engineering
   - Created FamilySize feature
   - Converted categorical variables into numeric form

4. Model Building
   - Logistic Regression model trained using train-test split (80-20)

5. Model Evaluation
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

---

## 📈 Model Performance

- Logistic Regression Accuracy: ~82%

---

## 🚀 How to Run the Project

1. Clone the repository:
   git clone https://github.com/TECHLORIC/Titanic-Survival-Prediction.git

2. Install required libraries:
   pip install -r requirements.txt

3. Run the notebook:
   jupyter notebook Titanic_Model.ipynb

---

## 📬 Author
Kabeer Gupta
