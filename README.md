# Airbnb Listings Analysis 🏠

An end-to-end data analysis project on Airbnb listings — covering data cleaning in Python, KPI building in MySQL, and interactive dashboard creation in Power BI.

---

## 📌 Project Overview

Airbnb is an online marketplace connecting hosts with travelers worldwide. This project performs Exploratory Data Analysis (EDA) on Airbnb listings to identify key factors affecting:

- Pricing and price distribution across countries
- Availability and occupancy trends
- Review patterns and ratings
- Listing performance and amenity impact

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python (Google Colab) | Data cleaning and feature engineering |
| MySQL | KPI queries and aggregations |
| Power BI | Dashboard and visualizations |

---

## 📁 Project Structure
airbnb/
│
├── AirBnb case study.pbix        # Power BI dashboard
├── airbnb.csv                    # Raw dataset (14,456 rows)
├── Airbnb_cleaned2.csv           # Cleaned dataset (13,621 rows)
├── newlisting.csv                # New listing price comparison
├── rating.csv                    # Country-level premium ratio
├── Documentation.docx            # Full project report
└── README.md
---

## 🧹 Data Cleaning Summary

Cleaning was done in Python on Google Colab:
- 🔗 [Colab Notebook 1](https://colab.research.google.com/drive/1jfdU64AUVLTs579SKbYlN0U2-wCrnxmC)
- 🔗 [Colab Notebook 2](https://colab.research.google.com/drive/1lr_9yB5MGJDQ9XulxOPQZG4oUxyN2mFr)

| Metric | Raw File | Cleaned File |
|--------|----------|--------------|
| Rows | 14,456 | 13,621 |
| Columns | 13 | 17 |
| Duplicate IDs | 652 | 14 |

Key transformations:
- Converted text fields to numeric types
- Split compound columns into structured attributes
- Created binary amenity indicators (Wi-Fi, Kitchen, Parking)
- Normalized price field to Price_in_Rupees

---

## 📊 Dashboard

The Power BI dashboard covers:
- Country-wise average pricing
- Rating distribution and premium listings
- New vs existing listing price comparison
- Host-level performance metrics

Open AirBnb case study.pbix in Power BI Desktop to explore.

---

## 👤 Author

Abhishek Gupta
M.Sc. Mathematics and Computing — NIT Manipur