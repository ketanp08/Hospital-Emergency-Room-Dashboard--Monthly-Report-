# 🏥 Hospital Emergency Room Dashboard – Monthly Report

An interactive, month-wise dashboard that tracks patient flow, waiting time, satisfaction, admissions, demographics and department referrals for the Emergency Room of **MediCare Hospital**.


---

## 📌 Project Overview

Emergency rooms run under constant pressure. Hospital management needs a quick view of **how many patients arrive, how long they wait, how satisfied they are, and where they are referred**. This dashboard turns raw ER records into a single-page report that can be filtered by **month** and **year**.

## 🎯 Objectives

- Monitor monthly patient volume in the ER
- Measure average patient wait time and satisfaction
- Understand admitted vs. not-admitted patients
- Analyse patients by age group and gender
- Identify which departments receive the most referrals
- Support decisions on staffing, resources and service quality

## 📊 Dashboard Components

| Section | Description |
|---|---|
| **Month & Year Slicers** | Filter the report by month (Apr–Mar financial year) and year (2023 / 2024) |
| **KPI Cards** | Number of Patients, Average Wait Time, Patient Satisfaction Score (with trend sparklines) |
| **Admission Status** | Count and % of Admitted vs. Not Admitted patients with progress bars |
| **Patients by Age Group** | Column chart across 0-9, 10-19 … 70-79 |
| **Patient Attend Status** | Pie chart of patient attendance split |
| **Gender-wise Analysis** | Donut chart of Female vs. Male patients |
| **Patients by Department Referral** | Bar chart: Cardiology, Gastroenterology, General Practice, Neurology, Orthopedics, Physiotherapy, Renal, None |

## 🔍 Key Insights (July view)

- **464 patients** visited the ER in July, with an **average wait time of 34.72** and a **satisfaction score of 4.99**.
- **Gender split is nearly even:** 228 female (49%) and 236 male (51%).
- **Most common age group is 20–29 (71 patients)**; the lowest is 60–69 (37 patients).
- **280 patients (~60%) needed no department referral**, meaning most cases were handled directly in the ER.
- **General Practice (87)** and **Orthopedics (54)** are the top referral departments, followed by Cardiology (12) and Physiotherapy (11).
- Renal (3), Gastroenterology (8) and Neurology (9) have very few referrals.

## 🛠️ Tools & Technologies

- **Data cleaning & modelling:** _(e.g., Excel / Power Query / SQL / Python – update with what you used)_
- **Visualisation:** _(e.g., Excel PivotCharts & Slicers / Excel)_
- **Calculations:** _(e.g., DAX measures / Excel formulas – update)_

## 🧮 Metrics Defined

| Metric | Definition |
|---|---|
| No. of Patients | Count of ER visits in the selected month/year |
| Average Wait Time | Mean time from arrival to being seen (state your unit, e.g. minutes) |
| Patient Satisfaction Score | Average rating given by patients (state your scale) |
| % Status | Share of admitted / not-admitted patients out of total |

## 📁 Repository Structure

```
├── README.md
├── data/
│   └── hospital_er_data.xlsx      # dataset (remove or anonymise if sensitive)
├── dashboard/
│   └── Hospital_ER_Dashboard.xlsx # or .pbix
└── images/
    └── dashboard.png              # dashboard screenshot
```

## ▶️ How to Use

1. Download the dashboard file from the `dashboard/` folder.
2. Open it in Excel / Power BI.
3. Use the **month buttons** on the left and the **year selector** at the top to filter.
4. All charts and KPIs update automatically.

## 🚀 Future Improvements

- Add day-of-week and hour-of-day arrival analysis
- Compare wait time against a target/benchmark
- Add triage level / severity analysis
- Add month-over-month and year-over-year comparison

## 👤 Author

**Ketan Patil**
Data Analyst | Python · SQL · Power BI · Excel
📍 Pune, India


---

⭐ If you found this project useful, consider giving it a star!
