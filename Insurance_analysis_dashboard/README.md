
# 🛡️ Insurance Analysis Dashboard

This project presents an interactive **Insurance Analysis Dashboard** designed to provide insights into insurance claim patterns, fraud detection, demographics, and geographic trends.  
It helps stakeholders identify high-risk areas, analyze claim behavior, and support data-driven decisions for fraud prevention and business optimization.

<img width="1060" height="663" alt="image" src="https://github.com/user-attachments/assets/8829920c-a145-4c98-a083-ed0107166493" />

---

## 📌 Key Features

### ✅ **1. KPI Summary Cards**
The dashboard highlights the most important insurance metrics:

- **Total Claims:** 1000  
- **Total Claim Amount:** 53M  
- **Total Fraud Cases:** 247  
- **Fraud Rate:** 0.25 (25%)  

These KPIs provide a quick snapshot of overall business performance and fraud exposure.

---

## 📊 Visualizations Included

### **2. Total Claim Amount by Incident State**
A bar chart showing states contributing the highest claim amounts:
- **NY (14.8M)**  
- **SC (13.5M)**  
- **WV (10.9M)**  
- **VA, NC, PA, OH**  

This helps identify high-risk or high-cost states.

---

### **3. Fraud vs Non-Fraud Cases by State**
A comparative horizontal bar chart showing:
- Number of **fraud cases**  
- Number of **legitimate (non-fraud) cases**  

States like **SC** and **NY** show high fraud involvement, indicating priority states for fraud analysis.

---

### **4. Geographical Claim Analysis (Map View)**
A map visualization showing:
- Claim distribution across the U.S.  
- Geographic hotspot identification  

Useful for **location-based risk assessment** and underwriting decisions.

---

### **5. Total Claims by Gender**
A donut chart showing:
- **Male:** 537 claims  
- **Female:** 463 claims  

Insight: Gender distribution is nearly balanced.

---

### **6. Total Claims by Month**
A line chart showing the monthly trend:
- January: 516  
- February: 472  
- March: 12  

This helps identify **seasonal claim patterns** and monthly fluctuations.

---

## 🎯 Insights From Analysis

- Fraud rate is relatively high (**25%**), requiring strong fraud detection mechanisms.
- States such as **NY, SC, and WV** contribute the highest financial losses.
- Fraud cases are concentrated in certain states, indicating possible fraud networks.
- Claims are well-distributed across genders.
- Monthly claims show drastic reduction in March (might be seasonal or incomplete data).

---

## 🛠️ Tools & Technologies Used

- **Power BI** for dashboard creation  
- **DAX** for calculated measures  
- **Data Cleaning & Preparation** (Power Query)  
- **Excel/CSV** as data sources  

---

## 📁 Files Included

- `Insurance Dashboard.pbix` — Power BI dashboard file  
- `insurance_data.csv` — Raw dataset (if included)  
- `README.md` — Project documentation  

---

## 🚀 How to Use

1. Open the `.pbix` file in **Power BI Desktop**  
2. Refresh the data source if required  
3. Interact with slicers such as:
   - Incident city  
   - State  
   - Gender  
   - Date  
4. Explore trends, high-risk zones, and fraud patterns  

---

## 📌 Future Enhancements

- Add machine learning fraud detection predictions  
- Include policyholder demographic segmentation  
- Add drill-through pages for individual fraud case analysis  
- Integrate time series forecasting  

---


