# 🔥 Calories Burnt Prediction

This project predicts the number of **calories burnt during physical activity** using **machine learning techniques**.  
It leverages exercise and calorie datasets, applies data preprocessing, and trains regression models to estimate energy expenditure.

---

## 📌 Project Overview
- Load and preprocess **exercise data** and **calories data**.
- Merge datasets to create a single structured dataframe.
- Perform **exploratory data analysis (EDA)** with visualization (Seaborn, Matplotlib).
- Train a **regression model** (XGBoost Regressor) to predict calories burnt.
- Evaluate model performance with metrics such as **R² score and Mean Absolute Error (MAE)**.

---

## 🛠️ Tech Stack
- **Python**
- **NumPy, Pandas** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Train/test split, evaluation metrics  
- **XGBoost** – Regression model  

---

## 📂 Dataset
The project uses two CSV files:
- `calories.csv` – Contains calorie expenditure data  
- `exercise.csv` – Contains exercise details (e.g., duration, gender, age, heart rate, body temperature, etc.)  

The datasets are merged for training.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Shaajithsalihundam/Calories-Burnt-Prediction.git
   cd Calories-Burnt-Prediction

