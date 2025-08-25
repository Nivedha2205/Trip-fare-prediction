Statistical Data Analysis of Taxi Fare by Payment Type

📌 Project Overview
This project analyzes NYC Taxi Trip Records to understand how payment methods (Card vs Cash) impact fare revenue.
Using statistical data analysis, the project provides insights into customer behavior and revenue optimization strategies for taxi drivers.

🎯 Objectives
Check if there is a clear difference in taxi fare revenue between cash and card payments.
Use hypothesis testing and regression to find meaningful insights.
Provide data-driven recommendations to improve driver earnings.

📊 Dataset
Source: NYC Yellow Taxi Trip Records
Relevant Features Used:
passenger_count (1–5)
payment_type (Card / Cash)
fare_amount
trip_distance (miles)
duration (minutes, derived from pickup/dropoff time)

🔎 Methodology
Data Cleaning – Removed invalid values, kept only card/cash payments, filtered passengers (1–5).
Exploratory Data Analysis (EDA) – Visualized payment type distribution, fare amounts, and passenger counts.
Hypothesis Testing (t-test) – Checked if card and cash fares are significantly different.
Regression Analysis – Studied the relationship between trip duration and fare amount.

📈 Key Findings
67% of trips were paid by card.
Card payments usually had higher fares and longer trips.
T-test confirmed a significant difference between card and cash fares.
Encouraging card payments can help drivers earn more revenue.

💡 Recommendations
Provide incentives for card payments (discounts, loyalty points).
Make card transactions seamless and secure to increase adoption.
Focus marketing efforts on digital payments to boost driver income.

🛠️ Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
Jupyter Notebook
🚀 Future Work
Add tip amount analysis to study tipping patterns.
Explore time-based trends (peak hours, weekdays vs weekends).
Build predictive models for fare and revenue forecasting.
📊 Dataset
The dataset used in this project is from the NYC Yellow Taxi Trip Records.
