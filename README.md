# 📊 Power BI NPS Dashboard

This repository contains a Power BI dashboard that analyzes **Net Promoter Score (NPS)** performance for India's top motorcycle companies, covering data from **April 2024 to March 2025**.

---

## 🧾 Dashboard Overview

The dashboard is divided into **three main pages**:

### 1️⃣ Guidelines
- Brief instructions on using and navigating the report
- Definitions and logic behind the NPS & NP% calculations

### 2️⃣ VCS (Visual Company Scorecard)
- Company-wise and product-wise NPS scorecards
- Monthly trends across dealers, states, and customer segments
- Logos are used to represent each company for better visualization

### 3️⃣ Tables & Personalize
- Detailed data tables with slicers and filters
- Ability to personalize columns
- Visual indicators for Promoters, Passives, and Detractors

---

## 🔍 Key Metrics

### 🎯 Net Promoter Score (NPS)
> **Formula:**  
> \[
> \text{NPS} = \left( \frac{\text{Promoters} - \text{Detractors}}{\text{Total Responses}} \right) \times 100
> \]

| Rating Range | Category     |
|--------------|--------------|
| 9–10         | Promoter     |
| 7–8          | Passive      |
| 1–6          | Detractor    |

---

### 🔢 NP% (Negative Percentage)
> **Formula:**  
> \[
> \text{NP%} = \left( \frac{\text{Passive + Detractors}}{\text{Total Responses}} \right) \times 100
> \]

---

## 🛠 Tools Used

- Microsoft Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Python (for synthetic data generation)  
- GitHub (Version control)

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `NPS_Motorcycle_Final_20160.csv` | Final dataset (20,160 rows) |
| `Power-BI_NPS-Dashboard.pbix`    | Power BI report with all visuals and logic |
| `README.md`                      | This documentation file |

---

## 🖼 Screenshot Previews

> 📌 Place your screenshots in a folder named `images/` inside the repo.

```plaintext
Power-BI_NPS-Dashboard/
│
├── images/
│   ├── guidelines_page.png
│   ├── vcs_page.png
│   ├── tables_page.png
│
├── Power-BI_NPS-Dashboard.pbix
├── NPS_Motorcycle_Final_20160.csv
└── README.md
