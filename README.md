# Medical Device Reliability & Maintenance Analysis  
*Power BI Dashboard*

## 📌 Project Overview

This project analyzes medical device performance by examining failure events, downtime, maintenance frequency, and and cost across multiple equipment types and manufacturers.  
The objective is to build a three-page Power BI dashboard that provides operational visibility, supports engineering decisions, and identifies high-risk devices requiring prioritization.

This dashboard was created as part of a real-world portfolio exercise to demonstrate practical BI skills relevant to engineering, healthcare, and maintenance analytics.

---

## 📜 Dataset & Context

The dataset contains anonymized information about medical devices, including:

- Device type, model, and manufacturer  
- Failure event counts  
- Downtime (hours)  
- Maintenance frequency and cost  
- Maintenance class (criticality level)  
- Country and purchase date  

This dataset enables realistic analysis of equipment reliability and operational cost structures.

**Dataset Source:**  
[Medical Device Failure Dataset (Anonymized)](https://www.kaggle.com/datasets/antoinepierreno/medical-device-failure-dataset-anonymized) — published on Kaggle by Antoine Pierreno.


---

## 📂 Project Structure
```
medical-device-reliability-dashboard/
│
├── Medical_Device_Failure_dataset.csv # Raw dataset
├── medical_device_dashboard.pbix # Power BI dashboard (3 pages)
├── README.md # Project documentation
│
├── /screenshots # Dashboard preview images (to be added)
│ ├── executive_summary.png
│ ├── failure_analysis.png
│ └── maintenance_workflow.png
│
└── /reports # Additional written analysis
│ ├── [FR]Rapport.md
│ └── [EN]Report.md
│
```

---

## 🔧 Usage Instructions

Clone the repository:

```bash
git clone https://github.com/belkaaloulmehdi/Medical-Device-Reliability-Dashboard.git
cd Medical-Device-Reliability-Dashboard
```

Open the Power BI dashboard:

```
medical_device_dashboard.pbix
```

Explore the three dashboard pages:

- **Executive Summary** — top KPIs and global equipment performance  
- **Failure Analysis** — trends, geographic breakdowns, and failure segmentation  
- **Maintenance Workflow** — maintenance cost, downtime patterns, and intervention frequency  

Use slicers to filter by device type, manufacturer, maintenance class, or country.

---

## 📊 Key Insights & Features

- Total failure counts, downtime, MTTR, and maintenance cost KPIs  
- Failure trends over time (year aggregation)  
- High-risk device ranking (failures, cost, downtime)  
- Manufacturer performance comparison  
- Maintenance workflow analysis: cost structure, frequency, downtime hotspots  

Designed for operational and engineering teams managing medical equipment.

---

## 🤝 Contributing
Suggestions and improvements are welcome.  
Feel free to fork the repository and submit a pull request.

---

## 📜 License
This project is open-source and available under the MIT License.

---

## 📌 Author
- **Marouan Mehdi Belkaaloul** - Data Analysis Enthusiast
