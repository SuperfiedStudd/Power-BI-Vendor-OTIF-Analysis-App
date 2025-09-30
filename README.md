# Power-BI-Vendor-OTIF-Analysis-App  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.vendor-otif-analysis?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/rHN9mGxKg-Y/0.jpg)](https://youtu.be/rHN9mGxKg-Y?si=khKbO5yxizlRHbDb)  

---

## Overview  

Timely and complete vendor deliveries are critical to seamless production and procurement workflows. The Vendor OTIF Analysis Dashboard provides actionable visibility into vendor delivery performance—helping teams monitor delays, evaluate fulfillment quality, and identify systemic inefficiencies.  

By comparing expected vs. actual delivery durations and categorizing orders by condition and timeliness, this dashboard supports vendor accountability and proactive supply chain optimization. Operations and procurement leaders can use these insights to negotiate better SLAs, address delay causes, and ensure consistent material flow.  

---

## Technical Framework  

The dashboard is powered by a structured Excel dataset that captures delivery dates, expected timelines, order status, and fulfillment condition.  

**Key components:**  
- **Data Source:** Manually maintained Excel files recording purchase orders, vendor names, expected vs. actual delivery dates, and reasons for non-delivery  
- **Data Preparation:** Performed using Power Query to format dates, calculate delivery gaps, and classify delivery conditions (Full or Partial)  
- **Data Model Dimensions:**  
  - Time (Calculated Delivery Gaps in Days)  
  - Vendor  
  - Delivery Status (Received / Not Received)  
  - Delivery Condition (Full / Partial)  
  - Delivery Timing (Late / Early / On-Time)  
  - Reason for Delay (for pending deliveries)  

This model is extendable to ERP or procurement systems with delivery tracking modules.  

---

## Interactive Filters  

Filters provide flexibility for user-driven insights and targeted issue detection:  
- **Vendor:** Analyze performance by supplier across all metrics and timelines  
- **Condition:** Separate analysis by Full or Partial delivery fulfillment  

These filters help isolate supplier issues, identify recurring shortfalls, and support corrective action planning.  

---

## Dashboard Highlights  

**KPI Cards – Average Delivery Duration**  
- Average Expected Delivery (Days): The planned delivery timeline across all purchase orders  
- Average Actual Delivery (Days): The real delivery performance—used to detect systematic delays  

**Pie Chart – Orders by Condition**  
Breaks down orders into Full vs. Partial deliveries, offering insight into vendor compliance and order fulfillment quality.  

**Bar Chart – Orders by Delivery Timing**  
Categorizes deliveries into Late, Early, and On-Time, helping procurement teams pinpoint timing issues and set realistic vendor expectations.  

**Table – Purchase Orders Not Yet Received**  
Lists open POs with expected delivery days, days past due, and the reason for delay—enabling real-time exception handling and vendor follow-up.  

**Table – Purchase Orders Received**  
Summarizes actual vs. expected delivery days for completed orders, with delivery condition noted. This helps benchmark vendor reliability over time.  

---

## Screenshots  

### Dashboard Overview 
![Dashboard Overview](https://github.com/SuperfiedStudd/Power-BI-Vendor-OTIF-Analysis-App/blob/main/docs/dashboard_overview.png?raw=true)  

### Purchase Orders Table 1  
![Purchase Orders Table 1](https://github.com/SuperfiedStudd/Power-BI-Vendor-OTIF-Analysis-App/blob/main/docs/purchaseorderstable1.png?raw=true)  

### Purchase Orders Table 2  
![Purchase Orders Table 2](https://github.com/SuperfiedStudd/Power-BI-Vendor-OTIF-Analysis-App/blob/main/docs/purchaseorderstable2.png?raw=true)  

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshots for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.vendor-otif-analysis?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

This Vendor OTIF Analysis Dashboard transforms raw delivery data into a robust evaluation tool—supporting smarter sourcing decisions, stronger vendor relationships, and a more resilient supply chain.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  
