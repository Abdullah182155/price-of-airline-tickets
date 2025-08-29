# Flight Price Prediction

This project predicts flight ticket prices using machine learning, specifically a **Random Forest Regressor**. The notebook provides a full end-to-end workflow from data preprocessing to model evaluation and sample predictions.

## 📂 Dataset

The dataset `Clean_Dataset.csv` contains the following features:

- `airline` – Airline name
- `source_city` – Departure city
- `destination_city` – Arrival city
- `departure_time` – Departure time
- `arrival_time` – Arrival time
- `stops` – Number of stops
- `class` – Flight class (Economy/Business)
- `flight` – Flight code
- `duration` – Flight duration
- `days_left` – Days left before flight
- `price` – Target variable (flight price)

## 🛠 Features

- Handles **categorical and numerical features** using `ColumnTransformer`.
- Categorical features are **OneHotEncoded**.
- Numerical features are **StandardScaled**.

## 📈 Model

- **Random Forest Regressor** is used for prediction.
- Evaluated using **MAE**, **RMSE**, and **R²** metrics.
- Predictions are made on **random test samples** for comparison with true prices.

## 🚀 Workflow

1. Import libraries  
2. Load and explore dataset  
3. Preprocess features  
4. Split dataset into training and testing sets  
5. Build a pipeline with Random Forest  
6. Train and evaluate the model  
7. Predict random samples and compare results  

## 📊 Results

- The model predicts flight prices effectively and captures non-linear relationships in the data.
- Performance metrics allow assessment of model accuracy and reliability.

## ⚡ Notes

- The notebook can be extended to use other regression models like Gradient Boosting, XGBoost, or CatBoost.
- Hyperparameter tuning can improve Random Forest performance.

## 📌 Author

**Abdullah Emara**  
Email: Abdullah.Ashraf.Emara@gmail.com  
GitHub: [https://github.com/Abdullah182155](https://github.com/Abdullah182155)
