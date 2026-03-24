## Cab Fare Prediction using Machine Learning

##  Project Overview
This project aims to predict cab fares based on various factors such as distance, time, and passenger count using Machine Learning techniques.

The model helps estimate the fare amount for taxi rides, similar to real-world applications like Uber and Ola.

---

##  Dataset
- Dataset: Uber Fare Dataset
- Features:
  - pickup_datetime
  - pickup_latitude, pickup_longitude
  - dropoff_latitude, dropoff_longitude
  - passenger_count
  - fare_amount (Target Variable)

---

## Technologies Used
- Python 
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Steps Performed
### 1. Data Preprocessing
- Handled missing values
- Removed outliers (negative fares, extreme coordinates)
- Converted datetime into useful features:
  - Hour
  - Day
  - Month

---

### 2. Feature Engineering
-  Distance calculated using Haversine Formula
-  Time-based features extracted
-  Removed invalid passenger counts

---

### 3. Exploratory Data Analysis (EDA)
- Fare distribution
- Distance vs Fare relationship
- Passenger count impact
- Heatmaps & correlation analysis

---

### 4. Model Building

Models used:
- Linear Regression
- Decision Tree
- Random Forest

---

##  Model Performance
- RMSE: (9.635767939908504)
- R² Score: (0.0015027341738323985)

---

---

##  Key Insights
- Distance is the most important factor affecting fare
- Peak hours increase fare slightly
- Outliers significantly impact predictions

---

##  Project Screenshots

### Dataset Preview
<img width="1905" height="968" alt="Screenshot 2026-03-18 220308" src="https://github.com/user-attachments/assets/3745459d-f668-4ada-8b82-ffbc3a9fa425" />


### Fare vs Distance
<img width="1263" height="830" alt="Screenshot 2026-03-18 222616" src="https://github.com/user-attachments/assets/c04c76c1-c7bc-4369-91a9-bf0cfe612937" />


### Model Performance
<img width="822" height="214" alt="Screenshot 2026-03-18 222553" src="https://github.com/user-attachments/assets/e708c4a6-46c6-41aa-92ef-9540783e2484" />


##  How to Run
1. Clone the repository:
```bash
git clone https://github.com/Deepika4456/cab_fare_prediction
