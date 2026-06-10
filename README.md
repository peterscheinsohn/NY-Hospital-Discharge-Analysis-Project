# Hospital Discharge Intelligence (SPARCS 2021)

Evidence Pilot 01 for **Health Tech Scout**: using real-world hospital discharge data to identify cost, length-of-stay, payer, and provider-level signals that can inform healthtech opportunity mapping.

This is not a synthetic training dataset. The project uses 2.05M de-identified inpatient discharge records across New York State hospitals to explore where clinical and operational burden becomes visible in public healthcare data.

## Explore the project

- **Interactive dashboard**: [Open Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjk5N2M2NTQtZGMxOC00ZjczLWEyNzgtNTg1MDc3ODk0ZWU3IiwidCI6IjcyYjM0ZmM2LTE1OTctNGRiOC1iYTFlLTA0ZmZlOGQzOTMwOSJ9)
- **Static dashboard preview**: [PDF preview](Hospitals_discharges_2021_USA.pdf)
- **Data cleaning notebook**: [Python / Pandas notebook](eda_cleaning%20(1).ipynb)

## Why this matters

Healthtech scouting should start with real healthcare problems, not only with company descriptions or technology labels. Hospital discharge data can help reveal where patient complexity, provider workload, payer mix, and financial pressure concentrate.

This pilot explores how public real-world data can support questions such as:

- Which diagnosis groups are associated with unusually high median costs?
- Where do long hospital stays suggest care coordination or aftercare challenges?
- How do charges, costs, payer groups, and mortality risk differ across segments?
- Which patterns could point toward relevant healthtech use cases such as discharge planning, care navigation, remote monitoring, hospital analytics, or cost transparency?

## Health Tech Scout angle

This project is designed as an evidence layer for a broader Health Tech Scout concept:

1. Start with a measurable healthcare burden.
2. Translate the burden into practical use cases.
3. Map companies and technologies that may address those use cases.
4. Keep the analysis transparent, sourced, and easy to challenge.

The dashboard is therefore not only a portfolio artifact. It is a small prototype for connecting healthcare data analysis with market and product intelligence.

## Selected findings

- "Effect of foreign body entering opening" showed an approximately $90K median cost in the analyzed data, making it one of the highest-cost diagnosis groups in the dashboard.
- Maltreatment and abuse-related cases showed an average stay of 37 days, far longer than many common respiratory conditions.
- Several service lines showed charges around 3-3.5x actual care costs; childbirth had one of the highest markup ratios in the analysis.
- Medicare discharges showed higher average cost than Government/Public payer cases in this dataset view.
- Medicare patients had a much higher share of Major or Extreme mortality risk than Private Insurance patients.

These findings are descriptive signals, not causal conclusions.

## Data source

- **Dataset**: Hospital Inpatient Discharges (SPARCS De-Identified) 2021
- **Official source**: [New York State Department of Health](https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/tg3i-cinn)
- **Kaggle mirror**: [Hospital Inpatient Discharges Dataset](https://www.kaggle.com/datasets/bhautikmangukiya12/hospital-inpatient-discharges-dataset)
- **Scope used here**: 2.05M records, 202 hospitals, 2021, fully de-identified

The SPARCS de-identified file contains discharge-level detail on patient characteristics, diagnoses, treatments, services, and charges. It does not contain protected health information under HIPAA.

## Method

- Cleaned and reduced the raw dataset from 32 columns to 14 analysis-ready fields with Python and Pandas.
- Modeled and transformed the data with Power Query.
- Built DAX measures for cost, charges, length of stay, payer comparison, and risk segmentation.
- Designed a Power BI dashboard focused on healthcare burden, provider variation, and financial signals.

## Tools

Python · Pandas · Power Query · DAX · Power BI

## Limitations

- This is a descriptive analysis, not a causal study.
- The dataset covers New York State inpatient discharges in 2021 and is not directly transferable to DACH or EU healthcare systems.
- Diagnosis-level patterns may reflect coding, case mix, hospital specialization, and other contextual factors.
- The dashboard should be used for exploration and hypothesis generation, not for medical, reimbursement, or policy decisions.

## Project note

This was my first Power BI project, built as a focused 1-2 week portfolio pilot. The analytical decisions are mine; AI tools were used for syntax support and design feedback.

My professional interest is the intersection of clinical research, real-world evidence, healthcare data analytics, and healthtech market intelligence.

---

**Peter Scheinsohn, Ph.D.**  
[LinkedIn](https://www.linkedin.com/in/peterscheinsohn) · peter.scheinsohn@gmail.com
