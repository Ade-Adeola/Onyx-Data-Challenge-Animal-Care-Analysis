# Onyx-Data-Challenge-Animal-Care-Analysis

## 📌 Overview
This project analyzes **animal shelter operations data** to understand **intake patterns, shelter pressure, and outcome performance** over time.

The goal is to identify:
- What drives intake volume
- How animals move through the shelter
- How outcomes such as adoption and live release evolve
- Where operational improvements can improve animal welfare

This project was completed as part of the **#dataDNA Challenge by Onyx Data**.

---

## 🎯 Objectives
- Analyze intake trends and seasonality
- Identify animal demographics driving intake pressure
- Evaluate outcome performance (alive, dead, adoption)
- Measure adoption effectiveness and live release rates
- Support insights with interactive Power BI visuals

---

## 🗂 Dataset
The dataset contains historical animal shelter records including:
- Animal details (type, sex, age, color)
- Intake information (date, condition, type, reason)
- Outcome information (type, subtype, live/dead status)
- Geographic data (jurisdiction, latitude, longitude)
- Derived metrics such as length of stay

The raw dataset is available in the `/dataset` folder.

---

## 📊 Dashboard Structure

### Page 1 — Intake Overview
This page focuses on **what comes into the shelter**.

Key analyses:
- Intake trends over time (daily, weekly, monthly, quarterly)
- Total intakes and average length of stay
- Intake distribution by animal type, age group, sex, and condition
- Geographic distribution of intakes by jurisdiction

**Key insight:**  
Infants and cats account for the highest intake volumes, with strong seasonal and geographic patterns.

![Intake Overview](images/intake_overview.png)

---

### Page 2 — Outcome Overview
This page focuses on **what happens after intake**.

Key analyses:
- Outcome trends (total, alive, dead)
- Adoption counts and adoption rates
- Live Release Rate (LRR) over time
- Outcome breakdown by animal type and outcome category

**Key insight:**  
While live outcomes dominate overall, adoption growth has not fully kept pace with rising intake pressure, especially during peak seasons.

![Outcome Overview](images/outcome_overview.png)

---

## 🔑 Key Findings
- Total intakes increased year-over-year, driven primarily by infants and cats
- Intake volume shows clear seasonality, peaking mid-year
- Most animals arrive in normal condition, indicating volume-driven pressure
- Live Release Rate remains strong (~79%) but shows pressure during high-intake periods
- Adoption channels perform well and represent opportunities for scaling

---

## 💡 Recommendations
- Target high-intake jurisdictions with preventive programs
- Expand foster and early-adoption pipelines for infants
- Scale proven adoption channels (web and walk-in)
- Plan staffing and capacity around seasonal peaks
- Reduce length of stay for high-volume animal groups

---

## 🛠 Tools & Skills Used
- Power BI
- DAX (measures & calculated columns)
- Data modeling
- Time-series analysis
- Geographic analysis
- Data storytelling & dashboard design

---

## 🔗 Live Interactive Dashboard
👉 [View Interactive Power BI Dashboard](PASTE_YOUR_POWER_BI_LINK_HERE)

---

## 🙏 Acknowledgements
Thanks to:
- Onyx Data
- ZoomCharts
- Smart Frames UI
- Enterprise DNA
- Data Career Jumpstart

for organizing and supporting the **#dataDNA Challenge**.

---

## 📌 Tags
Power BI · Data Analytics · Data Visualization · Animal Care · dataDNA
