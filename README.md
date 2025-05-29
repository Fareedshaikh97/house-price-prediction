# house-price-prediction
# Major Project
# House Price Prediction 🏠📈

## 📌 Objective
Develop a machine learning model to predict house prices based on features such as size, number of bedrooms, year built, garage size, etc.

## 📂 Dataset
- Source: [Kaggle House Prices](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- Contains training data with 79 explanatory variables describing aspects of residential homes.

## 🔧 Steps Performed

- 📊 Loaded and explored the dataset
- 🧹 Handled missing values
- 🔢 Encoded categorical variables
- 📏 Scaled numerical features
- 🤖 Applied **Linear Regression** and optionally **Decision Tree Regression**
- 🧪 Split into training and test sets
- 📈 Evaluated using **Mean Squared Error (MSE)** and **R-squared (R²)**

## 📊 Technologies Used

- Python 3
- Pandas
- Scikit-learn
- Jupyter Notebook / IDLE

## 📈 Results

- Achieved R² score of approximately **0.85**
- Model can predict house prices fairly accurately based on selected features

---

## 📎 How to Run

1. Clone this repo or download the script
2. Place `train.csv` from Kaggle in the same folder
3. Run the script using Python:

```bash
python house_price_prediction.py
