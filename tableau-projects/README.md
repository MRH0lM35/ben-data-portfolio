# 📊 Tableau Projects – Ben Phillips

This folder contains visualisation projects built using Tableau Desktop.

## Project: Email Metadata Dashboard

**Status:** In Progress  
**Tools:** Tableau, CSV, Python (data cleaning)

---

### 🎯 Objective

To visualise issues in CRM metadata including:
- Duplicate email entries
- Missing names
- Frequency of contact sources (e.g. signup, import)

The dashboard helps identify how clean the CRM is and supports future improvements.

---

### 📁 Folder Structure

```
tableau-projects/
├── tableau-datasets/        ← Raw datasets (CSV files)
├── exports/                 ← PNGs, PDFs of charts
├── ben-email-cleaner.twb    ← Tableau workbook file
└── README.md                ← This file
```

---

### 📥 Dataset Used

- `contacts_messy.csv`  
  Located in `tableau-datasets/`, this file contains contact records with inconsistent formatting, including duplicate emails, missing names, and inconsistent source entries.

---

### 📈 Planned Visuals

- Bar chart: Number of contacts by source  
- Pie chart: Percentage of entries missing email/name  
- Highlight table: Count of duplicate emails  

---

## 🧠 Notes

This dashboard will eventually be combined with outputs from my Python cleaning script (`project-1-email-cleaner`) to show before/after cleaning metrics.

Visualising this data helps explain the quality of the CRM and what needs to be improved before it can be used reliably.