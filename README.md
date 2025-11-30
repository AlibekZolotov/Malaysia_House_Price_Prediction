# Malaysia_House_Price_Prediction
Predicting house prices in Malaysia using Machine Learning (LightGBM).

---

## Project Overview

This project demonstrates how to:

* Clean and explore a real-world Malaysian housing dataset
* Engineer new features such as `Estimated_Total_Price`
* Handle categorical variables (Township, Area, State, Tenure, Type)
* Train a **LightGBM** regression model with early stopping
* Evaluate the model using **Mean Squared Error (MSE)** and **R² Score**

---

## Dataset

* Source: Kaggle (link to dataset if possible)
* Size: 2000 rows × 8 columns
* Columns:

| Column       | Description                  |
| ------------ | ---------------------------- |
| Township     | Name of the township         |
| Area         | Area name                    |
| State        | State name                   |
| Tenure       | Freehold / Leasehold         |
| Type         | House type                   |
| Median_Price | Median house price           |
| Median_PSF   | Median price per square foot |
| Transactions | Number of transactions       |

---

## Model Performance

* **Mean Squared Error (MSE)**: ~71,128,468,128
* **R² Score**: 0.60

> The model explains ~60% of the variation in house prices. More features or ensemble methods could improve performance further.

---

## Skills Demonstrated

* Data cleaning and exploration
* Feature engineering
* Handling categorical variables
* LightGBM regression with early stopping
* Model evaluation and visualization


This README makes your GitHub repo **look professional and clear**, highlighting both your technical skills and the project results.

