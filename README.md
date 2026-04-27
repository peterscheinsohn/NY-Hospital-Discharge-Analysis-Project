# NY Hospital Discharge Analysis (SPARCS 2021)

**My first Power BI project.** Real hospital data, not synthetic. 2.05M discharge records across 202 New York hospitals.

👉 **[View Dashboard Preview (PDF)](Hospitals_discharges_2021_USA.pdf)**  
📓 **[Data Cleaning Notebook (Python / Pandas)](eda_cleaning%20(1).ipynb)**

---

## Why this project

My previous portfolio project was Fintech — a domain I hardly understand. This time I picked healthcare, where I spent almost ten years in clinical trials. I specifically searched for real world evidence data, reduced 32 columns to 14 using Pandas, then explored the results in Power BI. Surprisingly, two financial columns — total charges and total costs — were enough to tell a meaningful story.

---

## What surprised me

The scale of heterogeneity. Effect of foreign body entering opening costs more than leukemia treatment — that I did not expect. Different hospitals specialize dramatically differently. And having spent years analyzing serious adverse events in clinical trials, I had never looked at the hospital stage as an economic burden before. That was new.

---

## Key findings

- Effect of foreign body entering opening: ~$90K median — most expensive diagnosis
- Maltreatment/abuse cases: 37 days average stay — 12x longer than respiratory conditions
- Hospitals charge 3–3.5x actual care costs — childbirth has highest markup at 3.88x
- Medicare: $26K per discharge vs $16K for Government/Public
- Medicare patients: 45.7% at Major or Extreme mortality risk vs 16.2% for Private Insurance

---

## Data source

- **Dataset**: Hospital Inpatient Discharges (SPARCS De-Identified) 2021
- **Official source**: [NY State Department of Health](https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/tg3i-cinn)
- **Kaggle**: [Hospital Inpatient Discharges Dataset](https://www.kaggle.com/datasets/bhautikmangukiya12/hospital-inpatient-discharges-dataset)
- 2.05M records · 202 hospitals · 2021 · Fully de-identified

---

## Tools

Python · Pandas · Power Query · DAX · Power BI

---

## Honest notes

- AI tools used for syntax help and design feedback. Analytical decisions are mine.
- First Power BI project, built over 1–2 weeks.

---

**Peter Scheinsohn, Ph.D.**  
[LinkedIn](https://www.linkedin.com/in/peterscheinsohn) · peter.scheinsohn@yahoo.de
