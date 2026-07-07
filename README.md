# 🏨 Hotel Booking Prediction

A Machine Learning project that predicts whether a hotel booking is likely to be **Canceled** or **Not Canceled** based on customer and booking details.

This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

---

## 📌 Project Overview

The objective of this project is to build a classification model that predicts booking cancellations using historical hotel booking data. This helps hotels reduce revenue loss and improve booking management.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Handling Missing Values
- Label Encoding
- Feature Scaling using StandardScaler
- Logistic Regression Model
- Model Evaluation
- Save Trained Model (.pkl)
- Save Scaler (.pkl)
- Prediction on New Data

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```
Hotel Booking/
│
├── hotel_booking_prediction.py
├── hotel_bookings.csv
├── hotel_booking_model.pkl
├── scaler.pkl
├── Graphs/
├── .gitignore
└── README.md
```

---

## 📊 Dataset

The project uses the **Hotel Booking Demand Dataset**, which contains booking information such as:

- Hotel Type
- Lead Time
- Arrival Date
- Number of Adults
- Number of Children
- Number of Babies
- Meal Type
- Country
- Market Segment
- Distribution Channel
- Reserved Room Type
- Deposit Type
- Customer Type
- Previous Cancellations
- Special Requests
- Booking Status

Target Variable:

- **is_canceled**
  - 0 → Not Canceled
  - 1 → Canceled

---

## ⚙️ Machine Learning Workflow

1. Import Dataset
2. Data Cleaning
3. Handle Missing Values
4. Exploratory Data Analysis
5. Encode Categorical Features
6. Scale Numerical Features
7. Train-Test Split
8. Train Logistic Regression Model
9. Evaluate Model
10. Save Model & Scaler

---

## 📈 Model Used

- Logistic Regression

The trained model is saved as:

```
hotel_booking_model.pkl
```

The fitted scaler is saved as:

```
scaler.pkl
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/Anu4477/Hotel-Booking.git
```

### Move to Project Folder

```bash
cd Hotel-Booking
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### Run

```bash
python hotel_booking_prediction.py
```

---

## 📊 Output

The project generates:

- Data Analysis
- Visualizations
- Model Accuracy
- Trained Model
- Saved Scaler
- Graphs Folder

---

## 🎯 Future Improvements

- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning
- Flask Web Application
- Streamlit Deployment
- Model Comparison Dashboard

---

## 👩‍💻 Author

**Anushka Singh**

GitHub: https://github.com/Anu4477

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!
