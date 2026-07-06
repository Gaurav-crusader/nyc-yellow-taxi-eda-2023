#  NYC Yellow Taxi — Exploratory Data Analysis (2023)

Exploratory Data Analysis on 2023 NYC Yellow Taxi trip records to uncover
operational, pricing, and passenger-experience insights.

---

##  Project Overview

As part of a simulated analyst role at a taxi operation entering the NYC
market, this project analyses the full year of 2023 Yellow Taxi trip data
(~35 million rows across 12 monthly files). A stratified sampling strategy
is used to keep the analysis manageable while preserving hourly and daily
demand patterns.

---

## Objectives

- Perform end-to-end EDA on large-scale real-world trip data
- Identify patterns in demand, trip duration, fare structure, and tipping
- Clean and handle messy data (duplicates, outliers, inconsistent columns)
- Derive actionable insights for operational and revenue decisions

---

##  Project Structure
nyc-yellow-taxi-eda-2023/
│
├── NYC_Taxi_EDA_Solved.ipynb   # Main analysis notebook
├── README.md
└── requirements.txt

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Plotting |
| Seaborn | Statistical visualisation |
| Pyarrow / Parquet | Efficient data storage |

---

## Key Steps

1. **Data Loading** — Stratified sampling across 12 monthly Parquet files
2. **Data Cleaning** — Fix duplicate columns, negative fares, missing values
3. **Outlier Handling** — Remove GPS errors, impossible durations, undefined payment types
4. **Exploratory Analysis** — Bivariate and multivariate analysis
5. **Visualisations** — Demand patterns, fare distributions, tip behaviour
6. **Insights & Conclusions**

---

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/Gaurav-crusader/nyc-yellow-taxi-eda-2023.git
cd nyc-yellow-taxi-eda-2023
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Download the data
Get the 2023 monthly Parquet files from the
[NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
page and place them in the project root.

### 4. Run the notebook
```bash
jupyter notebook NYC_Taxi_EDA_Solved.ipynb
```

---

## 📈 Sample Insights

- Demand peaks sharply during **morning and evening rush hours**
- **Airport trips** (JFK/LGA) show significantly higher average fares
- **Tipping behaviour** varies strongly by payment type
- Trip volume drops on weekends but average fare increases

---

##  Data Source

[NYC TLC Yellow Taxi Trip Records — 2023](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

---

##  Author

**Gaurav tode**
• [GitHub](https://github.com/Gaurav-crusader)

---
