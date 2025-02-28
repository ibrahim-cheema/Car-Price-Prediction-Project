# Car Price Prediction

## 📌 Overview
This project predicts car selling prices using multiple machine learning models. The dataset contains various attributes such as fuel type, seller type, and transmission type.

## 📊 Features Used
- **Fuel Type** (Categorical, Encoded)
- **Seller Type** (Categorical, Encoded)
- **Transmission** (Categorical, Encoded)
- **Other numerical attributes**

## 🚀 Models Implemented
- **Linear Regression**
- **Lasso Regression**
- **Random Forest Regressor**

## 🛠 Installation
Make sure you have Python installed, then install the required libraries using:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## 📂 Dataset
The dataset (`car_data.csv`) should be placed in the root directory of the project. It includes various attributes of cars along with their selling prices.

## 🔥 Steps Performed
1. Load and inspect the dataset.
2. Handle missing values (if any).
3. Encode categorical variables using `LabelEncoder`.
4. Split data into training and testing sets.
5. Train and evaluate:
   - **Linear Regression**
   - **Lasso Regression**
   - **Random Forest Regressor**
6. Compute R-squared error scores.
7. Visualize actual vs. predicted prices using scatter plots.

## ▶️ Usage
Run the script using:

```bash
python car_price_prediction.py
```
Ensure the dataset file is present in the same directory.

## 📈 Results
- The models predict the selling price of cars.
- Scatter plots show actual vs. predicted prices.
- R-squared error score is used for performance evaluation.



