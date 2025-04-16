# AqarSphere 🏡📊

**AqarSphere** is a machine learning project designed to predict house prices in Saudi Arabia based on various property features. The project uses data analysis, preprocessing, and model training to estimate property prices with high accuracy.

---

## 📁 Repository Structure

| File                          | Description |
|------------------------------|-------------|
| `AqarSphere.ipynb`           | Main Jupyter notebook with data analysis, preprocessing, and model training |
| `SA_Aqar.csv`                | Raw real estate data used in the project |
| `cleaned_aqar_data.csv`      | Cleaned version of the dataset |
| `processed_features.csv`     | Final dataset with encoded and scaled features |
| `house_price_model.pkl`      | Trained machine learning model (baseline) |
| `xgboost_model.pkl`          | XGBoost regression model |
| `scaler.pkl`                 | Scaler used to normalize data |
| `house_price_scaler.pkl`     | Scaler specific to target variable |
| `README.md`                  | Project documentation (you're reading it) |

---

## 🧠 Technologies Used

- **Python** 🐍
- **Pandas** for data wrangling
- **NumPy** for numerical computation
- **Matplotlib** & **Seaborn** for data visualization
- **Scikit-learn** for preprocessing and model evaluation
- **XGBoost** for advanced regression modeling
- **Jupyter Notebook** for development and demonstration

---

## 📊 Data Overview

The dataset contains real estate listings from Saudi Arabia, with features such as:

- Property type
- Area (m²)
- Location
- Price
- Number of rooms
- Number of bathrooms
- Age of property

---

## 🔍 Exploratory Data Analysis (EDA)


📸 **Example:**  
![download (4)](https://github.com/user-attachments/assets/9c58d6ab-6021-463b-b647-4df8d6001142)

📸 **Example:**  
![download (3)](https://github.com/user-attachments/assets/5caa1956-3206-4ac7-8b9a-38406c971698)

---

## 🧪 Model Training & Evaluation

The models trained include:

- **Linear Regression**
- **XGBoost Regressor**

Evaluation metrics used:
- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

![download (5)](https://github.com/user-attachments/assets/9f2d2cb0-1bd8-4bfe-9722-499b75fb4d4b)

---

## 🚀 How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/AbdulmalikDS/AqarSphere.git
cd AqarSphere
