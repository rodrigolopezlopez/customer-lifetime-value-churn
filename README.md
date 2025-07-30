# Customer Lifetime Value & Churn Analysis

This project analyzes driver behavior for a ride-sharing platform to understand **Customer Lifetime Value (LTV)** and **driver churn**.

## Key Insights:

* **Driver LTV:** Each new driver is estimated to generate **$132 USD** in profit for the platform before churning. This is based on an average fare of $13.84/trip, 48 trips per driver, and a 20% platform profit split.

* **Churn Rate:** Approximately **16.54%** of drivers churn, with an average tenure of **23 days**. Churning drivers typically show a **negative trend** in weekly ride activity before leaving.

* **Driver Engagement:** Most drivers are **occasional** (less than 20 rides/week) or **part-time** (20-40 rides/week). There's a strong correlation between lower engagement and higher churn, indicating a significant opportunity to increase overall rides by improving existing driver engagement.

## Analysis Details:

* **Data:** Driver and ride data (including timestamps, distance, duration, prime time).

* **Methodology:** Data cleaning, LTV calculation, churn identification (28 days of inactivity), and driver segmentation by weekly ride average.

* **Tools:** Python (Pandas, Matplotlib, Seaborn).

## How to Run:

1.  **Clone the repository:** `git clone <repository_url>`

2.  **Open the Jupyter Notebook:** `customer-lifetime-value-churn.ipynb` in Google Colab or your local Jupyter environment.

3.  **Run all cells** to reproduce the analysis.

## Future Work:

* Analyze longer data periods for more accurate LTV and churn trends.

* Develop predictive models for churn and optimize driver incentive programs.
