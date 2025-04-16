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

Insert graphs or screenshots here to visualize the data distribution and relationships between variables.

📸 **Example:**  
`![](images/eda_price_distribution.png)`

📸 **Example:**  
`![](images/eda_correlation_matrix.png)`

---

## 🧪 Model Training & Evaluation

The models trained include:

- **Linear Regression**
- **XGBoost Regressor**

Evaluation metrics used:
- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

📸 Insert model comparison plots here:  
`![](images/model_performance.png)`

---

## 🚀 How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/AbdulmalikDS/AqarSphere.git
cd AqarSphere
