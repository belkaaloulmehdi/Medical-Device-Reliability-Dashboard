# Medical Device Reliability Dashboard — Power BI Project

## 📌 1. Executive Summary

This project analyzes the reliability, maintenance behavior, and operational burden of medical devices across multiple manufacturers and device types.  
The Power BI dashboard highlights failure trends, downtime impact, and maintenance costs to support data-driven decisions in healthcare asset management.

The findings identify high-risk equipment categories, significant cost drivers, and opportunities to improve preventive maintenance strategies.

(INSERT SCREENSHOT PAGE 1 HERE)

---

## 📊 2. Dataset Description

**Source**: Kaggle – Medical Device Failure Dataset (Anonymized)  
**Rows**: 8,123  
**Columns** include:  
- Device Type  
- Manufacturer  
- Failure Event Count  
- Downtime (hrs)  
- Maintenance Frequency (annual events)  
- Maintenance Cost (USD)  
- Purchase Date  
- Maintenance Class (1–3)  
- Country  

The dataset represents anonymized operational and maintenance logs for medical equipment.

---

## 📈 3. Executive Summary Dashboard — Key Metrics

This page delivers the high-level operational KPIs:

- **Total Maintenance Cost:** $35.9M  
- **Mean Time To Repair (MTTR):** 11 hours  
- **Total Downtime:** 44K hours  
- **Total Failures:** 8K events  

**Visuals included:**  
- Failure Count by Device Type  
- Total Downtime by Manufacturer  

These charts help identify which device categories and manufacturers generate the largest operational burden.

(INSERT SCREENSHOT PAGE 1 VISUALS HERE)

---

## 🔍 4. Failure Analysis Dashboard

This page explores when and where failures occur.

**Key insights:**
- **Failures per Year:** fluctuating reliability with a noticeable dip in 2024  
- **Failures by Country:** varying failure volumes across regions  
- **Failures by Maintenance Class:** Classes 1 and 2 drive a significant portion of failures  

A detailed table lists high-risk devices with:
- Device ID  
- Manufacturer  
- Device Type  
- Failure Count  
- Maintenance Cost  
- Total Downtime  

This allows quick identification of assets requiring urgent attention.

(INSERT SCREENSHOT PAGE 2 HERE)

---

## 🛠️ 5. Maintenance Workflow Dashboard

This page focuses on maintenance operations and cost impact.

**Visuals included:**
- Average Maintenance Frequency by Device Type  
- Maintenance Cost by Manufacturer  
- Downtime by Device Type  

**Consolidated summary table:**  
Shows failure count, maintenance frequency, maintenance cost, and downtime for each device.

This view helps identify:
- Cost-intensive manufacturers  
- Devices causing the most operational interruption  
- Maintenance patterns across equipment categories

(INSERT SCREENSHOT PAGE 3 HERE)

---

## 🧭 6. Business Recommendations

- Prioritize preventive maintenance on devices with high maintenance frequency and high downtime.  
- Reevaluate contracts with manufacturers associated with excessive downtime or high maintenance costs.  
- Investigate regional differences in failure rates to uncover training gaps or environmental factors.  
- Consider replacing aging or high-cost assets based on total cost of ownership metrics.  
- Adjust maintenance schedules for devices with predictable failure patterns.

---

## ⚠️ 7. Limitations & Next Steps

**Limitations:**
- Dataset lacks device age, usage hours, and maintenance type, limiting root-cause analysis.  
- Several extreme values may represent logging errors or rare exceptional cases.  

**Next Steps:**
- Integrate MTBF and predictive failure modeling.  
- Add SLA and technician performance metrics.  
- Connect real operational data (usage hours, device age).  
- Automate report refresh and integrate with Smartsheet or SQL sources.

---

## 👤 Author

**Marouan Mehdi Belkaaloul**  
Data Analyst — Power BI, SQL, Python, Data Modeling  
