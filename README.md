# Customer Lifetime Value & Churn Analysis

This project analyzes driver behavior for a ride-sharing platform to understand **Customer Lifetime Value (LTV)** and **driver churn**.

## Key Insights:

* **Driver LTV:** Each new driver is estimated to generate **$132 USD** in profit for the platform before churning. This is based on an average fare of $13.84/trip, 48 trips per driver, and a 20% platform profit split.

* **Churn Rate:** Approximately **16.54%** of drivers churn, with an average tenure of **43 days**. Churning drivers typically show a **negative trend** in weekly ride activity before leaving.

* **Driver Engagement:** Most drivers are **occasional** (less than 20 rides/week) or **part-time** (20-40 rides/week). There's a strong correlation between lower engagement and higher churn, indicating a significant opportunity to increase overall rides by improving existing driver engagement.

## Analysis Details:

* **Data:** Driver and ride data (including timestamps, distance, duration, prime time).

* **Methodology:** Data cleaning, LTV calculation, churn identification (28 days of inactivity), and driver segmentation by weekly ride average.

* **Tools:** Python (Pandas, Matplotlib, Seaborn).

## Future Work:

* Analyze longer data periods for more accurate LTV and churn trends.

* Develop predictive models for churn and optimize driver incentive programs.

## Relevant Graphs:
<div align="center">
  <img src="https://github.com/user-attachments/assets/ca61d661-0f5d-4df1-b74c-95318982d226" alt="Graph 1" width="32%" />
  <img src="https://github.com/user-attachments/assets/3e16266b-8592-4ab5-a89c-9c43fb568f2b" alt="Graph 2" width="32%" />
  <img src="https://github.com/user-attachments/assets/7dfd2452-79c4-49c7-ad6f-06ad8152a9d4" alt="Graph 3" width="32%" />
</div>



