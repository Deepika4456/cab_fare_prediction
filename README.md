# cab_fare_prediction
Machine Learning project to predict cab fares using distance, time, and passenger data with regression models.
# 🚖 Cab Fare Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict cab fares based on various factors such as distance, time, and passenger count using Machine Learning techniques.

The model helps estimate the fare amount for taxi rides, similar to real-world applications like Uber and Ola.

---

## 📊 Dataset
- Dataset: Uber Fare Dataset
- Features:
  - pickup_datetime
  - pickup_latitude, pickup_longitude
  - dropoff_latitude, dropoff_longitude
  - passenger_count
  - fare_amount (Target Variable)

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🔍 Steps Performed
1. Data Collection
2. Data Cleaning
3. Feature Engineering
   - Distance calculation using Haversine formula
   - Extracting time features (hour, day, month)
4. Model Building
   - Linear Regression
5. Model Evaluation
   - RMSE
   - R² Score

---

## 📈 Model Performance
- RMSE: (your value)
- R² Score: (your value)

---
## 📸 Project Screenshots

### Dataset Preview
![Dataset](<img width="1905" height="968" alt="Screenshot 2026-03-18 220308" src="https://github.com/user-attachments/assets/3745459d-f668-4ada-8b82-ffbc3a9fa425" />
)

### Fare vs Distance
![Graph](<img width="1263" height="830" alt="Screenshot 2026-03-18 222616" src="https://github.com/user-attachments/assets/c04c76c1-c7bc-4369-91a9-bf0cfe612937" />
)

### Model Performance
![Output](<img width="822" height="214" alt="Screenshot 2026-03-18 222553" src="https://github.com/user-attachments/assets/e708c4a6-46c6-41aa-92ef-9540783e2484" />
)

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/cab-fare-prediction.git
