# 🏠 StaySpain – Operations & Inventory Analysis

## 📌 Overview

This project analyzes the performance of a short-term rental platform (Airbnb-like) from an operations and inventory management perspective.

The goal is to understand how listing configuration impacts availability and occupancy, and to identify actionable opportunities to optimize inventory performance.

---

## 🎯 Business Context

This analysis is part of a simulated business environment (2017–2021), using real-world data patterns from the Spanish tourism market.

The focus is not on building predictive models, but on:
- understanding operational drivers
- identifying inefficiencies in inventory
- translating data into business decisions

---

## 🔍 Key Questions

The project is structured around three core operational questions:

1. How does availability vary across cities and time horizons?
2. What is the impact of Instant Booking on occupancy?
3. How do listing characteristics (capacity, price, configuration) affect availability?

---

## 📊 Key Insights

- Availability varies significantly across cities, indicating different demand pressure levels
- Larger and more expensive listings tend to have higher availability (lower occupancy)
- Instant Booking increases occupancy on average, but its impact varies by city and segment
- Listing configuration (beds, bathrooms) has limited impact compared to price and capacity

---

## 💡 Business Implications

- Inventory performance is not homogeneous → segmentation is critical
- Pricing and capacity are key levers for optimization
- Platform-driven features (e.g., Instant Booking) should be applied selectively
- Not all listings require the same strategy

---

## 📁 Project Structure

Each folder contains a specific analysis, including:
- data preparation (ETL)
- KPI definition
- business conclusions

---

## 🛠️ Tools & Techniques

- Python (Pandas, NumPy)
- Data visualization (Matplotlib, Seaborn)
- Regression models (OLS, Logistic Regression)
- Business-oriented data analysis
