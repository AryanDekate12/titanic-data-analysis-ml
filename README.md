# 🚢 Titanic Data Analysis & Feature Engineering

## 📌 Project Overview
This project performs an end-to-end data analysis on the Titanic dataset.
It includes data cleaning, preprocessing, feature engineering, and visualization to uncover key insights about passenger survival.

---

## 📂 Dataset
Dataset used: Titanic - Machine Learning from Disaster (Kaggle)

The dataset contains information about passengers such as age, gender, class, fare, and survival status.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Steps Performed

### 1️⃣ Data Loading
- Loaded dataset using Pandas
- Explored structure using `.head()`, `.info()`, `.describe()`

### 2️⃣ Data Cleaning
- Handled missing values:
  - Age → filled with median
  - Embarked → filled with mode
- Dropped Cabin column due to excessive missing values

### 3️⃣ Data Manipulation
- Converted categorical data into numerical format:
  - Sex → encoded to 0 and 1
  - Embarked → one-hot encoding

### 4️⃣ Feature Engineering
- Created new features:
  - FamilySize = SibSp + Parch + 1
  - Title extracted from passenger names
- Grouped rare titles for better analysis

### 5️⃣ Data Visualization
- Survival count plot
- Gender vs Survival
- Age distribution
- Correlation heatmap

---

## 📊 Key Insights
- Females had a significantly higher survival rate than males
- Passengers in higher classes (Pclass 1) had better survival chances
- Smaller families had higher survival probability
- Age and fare showed correlation with survival

---

## ▶️ How to Run

1. Clone the repository:
git clone https://github.com/AryanDekate12/titanic-data-analysis-ml.git

2. Navigate to the project folder:
cd titanic-data-analysis-ml

3. Install dependencies:
pip install -r requirements.txt

4. Run Jupyter Notebook:
jupyter notebook

---

## 📁 Project Structure
titanic-data-analysis-ml/
│
├── titanic_analysis.ipynb
├── train.csv
├── requirements.txt
└── README.md

---

## 🚀 Future Improvements
- Apply Machine Learning models (Logistic Regression, Decision Tree)
- Build a prediction system
- Deploy as a web app using Streamlit

---

## 👨‍💻 Author
Aryan Dekate
Information Technology Engineer | Data Science Enthusiast
