# 🚀 Dynamic Pricing Engine (Machine Learning Project)

## 📌 Overview

This project implements a Machine Learning-based Dynamic Pricing Engine that adjusts prices based on demand-supply conditions to maximize revenue.

## 🧠 Problem Statement

Traditional pricing systems use fixed prices, which fail to adapt to changing market conditions.
This project solves that by dynamically adjusting prices using data-driven techniques.

## ⚙️ Approach

* Built a regression model using **Random Forest**
* Applied **feature engineering** (demand-supply ratio, pricing factors)
* Introduced **dynamic pricing logic** based on demand and supply
* Implemented **price constraints** to ensure realistic outputs

## 📊 Features Used

* Number of Riders (Demand)
* Number of Drivers (Supply)
* Location Category
* Time of Booking
* Vehicle Type
* Ride Duration

## 📈 Results

* Achieved **low MAE (~7.8)** indicating accurate predictions
* Improved simulated revenue by **~10–15% (realistic range)**
* Implemented pricing constraints to avoid unrealistic outputs

## 🔥 Key Highlights

* Combines **Machine Learning + Business Logic**
* Includes **Revenue Optimization Strategy**
* Real-world inspired pricing system (similar to Uber surge pricing)

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib

## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib
python dynamic_pricing.py
```

## 📌 Future Improvements

* Deploy using Flask API
* Add real-time data input
* Integrate Streamlit UI

---

⭐ If you found this useful, feel free to star the repo!

