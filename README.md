# 📊 Automated Sales Performance Analytics (SQL + Python + Reporting)

## 🔍 Project Overview

This project automates the analysis of **sales performance and field force effectiveness** using SQL and Python.
It calculates key KPIs, generates reports, and automatically distributes them via email.

---

## ⚙️ Automation Pipeline

### 🔄 Process Flow

1. Extract and transform data using SQL
2. Generate datasets:

   * Sales Achievement & Trend
   * Seen Rx (Prescription Tracking)
   * Doctor Call Activity
3. Process and prepare reports using Python
4. Automatically send reports to stakeholders via email

### ⏱️ Execution

The pipeline runs end-to-end and tracks execution time for performance monitoring.

---

## 🛠️ Tools & Technologies

* SQL (data extraction & KPI calculation)
* Python (automation & data processing)
* PyInstaller (executable packaging)
* PowerPoint (reporting)
* Email automation (SMTP)

---

## 📊 Key Metrics

* Sales Achievement %
* Sales Trend % (monthly projection)
* Seen Rx
* Doctor Call Activity

---

## 🧠 SQL Analysis Highlights

The SQL logic includes:

* Dynamic date calculations
* Monthly trend projection using:

  ```
  (SalesAmount / DaysElapsed * TotalDaysInMonth) / TargetAmount * 100
  ```
* Multi-level aggregation:

  * RSM (Regional Sales Manager)
  * FM (Field Manager)
  * MSO (Medical Sales Officer)
* Complex joins between target and sales data

---

## 🔎 Key Insights

* Identifies top-performing brands and regions
* Tracks sales growth trends over time
* Evaluates field force performance
* Links doctor engagement with sales outcomes

---

## 💼 Business Impact

This solution enables:

* Faster and automated reporting
* Data-driven decision-making
* Improved sales strategy
* Efficient monitoring of field force performance

---

## 📁 Project Structure

```
Automated-Sales-Performance-Analytics/
│
├── sql/
│   └── brand_performance_analysis.sql
│
├── python/
│   ├── main.py
│  
│
├── report/
│   └── brand_performance_report.pptx
│
├── spec/
│   └── sales_report_automation.spec
│
├── data/
│   └── brand_list.csv
│
└── README.md
```

---

## 📦 Executable Build

The project includes a PyInstaller configuration file to package the Python script into a standalone executable.

This allows users to run the reporting pipeline without installing Python.

---

## 🚀 Future Improvements

* Convert reporting to Power BI dashboard
* Automate data ingestion pipelines
* Add predictive analytics (forecasting)
* Integrate cloud-based data sources

---

## 📬 Contact

Feel free to connect with me on GitHub or LinkedIn for collaboration or feedback.
