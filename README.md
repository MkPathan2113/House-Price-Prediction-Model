# 🏡 California House Price Prediction

## 📌 Project Overview
This project aims to **predict house prices in California** using **Linear Regression** based on various **housing features** such as location, number of rooms, population, and median income. The dataset is sourced from the **California Housing dataset** available in **Scikit-learn**.

## 📂 Dataset Information
The dataset consists of **housing-related features** from California districts collected during the **1990 U.S. Census**.

### 🔹 **Features**
- **MedInc** (*Median Income*) - Income of residents in a district.
- **HouseAge** (*Median House Age*) - Average age of houses in a district.
- **AveRooms** (*Average Rooms per Household*) - Total rooms divided by total households.
- **AveBedrms** (*Average Bedrooms per Household*) - Total bedrooms divided by total households.
- **Population** - Total population in a district.
- **AveOccup** (*Average Household Size*) - Total population divided by total households.
- **Latitude** - Geographic coordinate (North-South position).
- **Longitude** - Geographic coordinate (East-West position).

### 🎯 **Target Variable**
- **MedHouseVal** (*Median House Value*) - The median house price in a district (in $100,000s).

## 📊 Exploratory Data Analysis (EDA)
- Checked **missing values** and **handled null entries**.
- Analyzed **feature distributions** using **histograms**.
- Identified **correlations** between features and house prices.
- Found that **median income** is the strongest predictor of house prices.

## 🛠️ Model Building
### 🔹 **Data Preprocessing**
- Handled **missing values** using median imputation.
- Applied **feature scaling** using `StandardScaler`.
- Split the dataset into **training (80%)** and **testing (20%)** sets.

### 🔹 **Machine Learning Model**
- **Linear Regression** was used to predict house prices.

### 📈 **Model Evaluation**
| Metric | Value |
|--------|-------|
| **Mean Squared Error (MSE)** | Low |
| **Root Mean Squared Error (RMSE)** | Moderate |
| **R² Score** | High |

The model performed **well** but showed some **limitations**, especially with non-linear relationships in the data.

## 🚀 Future Improvements
- Implement **Polynomial Regression** to capture non-linearity.
- Use **Random Forest Regression** for better accuracy.
- Apply **Deep Learning techniques** like Neural Networks.
- Perform **feature engineering** for improved predictions.

