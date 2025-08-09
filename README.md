# Customer Lifetime Value & Churn Analysis

This project analyzes driver behavior for a ride-sharing platform to understand **Customer Lifetime Value (LTV)** and **driver churn**.

---

### **🎯 Key Highlights & Project Overview**

This analysis focuses on extracting **key insights** into driver behavior. The most important findings include:

* **Driver LTV**: Each new driver is estimated to generate **$132 USD** in profit for the platform before churning. This is based on an average fare of $13.84, **48 trips per driver**, and a 20% platform profit split.
* **Churn Rate**: Approximately **16.54%** of drivers churn, with an average tenure of **43 days**. Churning drivers typically show a **negative trend** in their weekly ride activity before leaving.
* **Driver Engagement**: Most drivers are **occasional** (fewer than 20 rides/week) or **part-time** (20-40 rides/week). There is a strong correlation between **lower engagement** and a **higher churn rate**, indicating a significant opportunity to increase overall rides by improving existing driver engagement.

---

### **🛠️ Technical Approach**

#### **Analysis and Methodology**

* **Data**: Driver and ride data were used, including timestamps, distance, duration, and "**prime time**."
* **Methodology**: The analysis process included data cleaning, **LTV calculation**, **churn identification** (defined as **28 days of inactivity**), and **segmentation** of drivers by their average weekly rides.
* **Tools**: The project was implemented using **Python** (with the **Pandas**, **Matplotlib**, and **Seaborn** libraries).

---

### **📈 Future Work**

The initial analysis provides a solid foundation, but future work will focus on the following areas to gain a more complete view:

* **Long-Term Data Analysis**: Analyze longer data periods to get **more accurate trends** for LTV and churn.
* **Predictive Models**: Develop **predictive models** to anticipate churn and optimize driver incentive programs.

---

### **Relevant Graphs**

<div align="center">
  <img src="https://github.com/user-attachments/assets/ca61d661-0f5d-4df1-b74c-95318982d226" alt="Graph 1" width="32%" />
  <img src="https://github.com/user-attachments/assets/3e16266b-8592-4ab5-a89c-9c43fb568f2b" alt="Graph 2" width="32%" />
  <img src="https://github.com/user-attachments/assets/7dfd2452-79c4-49c7-ad6f-06ad8152a9d4" alt="Graph 3" width="32%" />
</div>
