# 🚌 Bus Journey Demand Forecasting - Hackathon Project

Predicting bus seat demand 15 days before journey date using historical booking and search data.

---

## 📌 Overview

This project focuses on **forecasting the number of seats booked** for future bus journeys using machine learning. The primary objective is to predict demand at the **route level** based solely on **historical data available up to 15 days before the journey**.

---

## 🔍 What the Project Does

- 📊 Trains an ML model using past **booking** and **search** behavior.
- ⏳ Predicts seat demand **15 days in advance** of each journey.
- 📁 Outputs predictions in the format required for submission.

---

## 📂 Repository Contents

### 🧠 Core Code
- `BusDemandForecasting.ipynb` – Complete Interactive Python Notebook with:
  - Data loading & preprocessing  
  - Feature engineering  
  - Model training & evaluation  
  - Final predictions  

### 📁 Datasets
- `train.csv` – Historical journey data with:
  - `source_id`, `destination_id`, `date_of_journey`, and `total_seats_booked` (target)
- `test_8gqdJqH.csv` – Journeys for which predictions are required (future dates).
- `transactions.csv` – Booking & search events:
  - Timestamps, booking/search counts, user region, and city tier information.

### 📄 Output Files
- `sample_Result.csv` – Submission template with correct format.
- `Result.csv` – Final output file with predicted seat counts.

### 📦 Others
- `requirements.txt` – Python dependencies needed to run the notebook.
- `README.md` – You’re reading it!

---

## ⚙️ Tech Stack

- Python (Pandas, NumPy, Scikit-learn, LightGBM)
- Interactive Python Notebook/Jupyter Notebook
- CSV-based structured data

---
