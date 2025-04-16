# 🩺 Healthcare: Advancing Healthcare Analysis through Data Insights

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow) ![Healthcare](https://img.shields.io/badge/Domain-Healthcare-blue) ![Status](https://img.shields.io/badge/Status-Completed-green)

![Healthcare-analytics](https://github.com/user-attachments/assets/a845f93a-6514-4463-91d1-f8c93d082628)




Welcome to the *Healthcare Analysis* Power BI project! 🚀 This project unlocks actionable insights from healthcare data, focusing on patient demographics, treatment outcomes, and hospital performance. With vibrant dashboards and robust analytics, it empowers stakeholders to optimize healthcare delivery. 🩺📊

---

## 📖 Project Overview

This project transforms raw healthcare data into meaningful insights through dynamic visualizations. Key focus areas include:

- **Patient Demographics** 👥: Age, gender, blood group, and diagnosis distributions.
- **Treatment Analysis** 💊: Costs, recovery ratings, and effectiveness across treatments.
- **Hospital Performance** 🏥: Patient load, recovery metrics, and cost comparisons.
- **Trends & Correlations** 📈: Relationships between patient load, recovery, and treatments.

The result is an interactive dashboard driving data-informed decisions. ✨

---

## 🧹 Data Preprocessing

The dataset comprises **1000 rows and 17 columns**, covering patient details, diagnoses, treatments, and hospital metrics. Preprocessing steps included:

- **Cleaning** 🧼:
  - Removed duplicates and resolved missing values (e.g., nulls in diagnosis/cost).
  - Standardized formats for dates, gender, and treatment types.
- **Transformation** 🔄:
  - Grouped ages into categories (Infant, Toddler, Child, Teen, Adult, Middle Age Adult, Senior Adult).
  - Aggregated costs and recovery ratings by hospital and diagnosis.
- **Feature Engineering** 🛠️:
  - Created columns for daily costs and recovery trends.
  - Categorized diagnoses as chronic (e.g., Diabetes) or acute (e.g., Flu).

These steps ensured a clean dataset for accurate analysis. ✅

---

## 📐 Custom Measures

Custom DAX measures enhanced analytical depth:

- **Average Recovery Rating** 📊: Mean recovery score across diagnoses and treatments.
- **Average Patients per Room** 🛏️: Hospital occupancy metric.
- **Patients per Doctor** 👩‍⚕️: Doctor workload to assess recovery impact.

These measures power dynamic visuals and trend analysis. 🔍

---

## 📈 Interactive Dashboard Features

The project features a **creative interactive dashboard** for seamless exploration:

- **Interactive Slicers** 🎚️:
  - Filter by Year, Diagnosis, Treatment Type, Age Group, Gender, Hospital, and Doctor.
- **Visualizations** 📉:
  - **Bar Charts**: Compare treatment costs and recovery ratings.
  - **Line Graphs**: Track seasonal trends.
  - **Stacked Columns**: Show gender-wise diagnoses.
  - **Heatmaps**: Highlight correlations (e.g., patient load vs. recovery).
  - **Donut Charts**: Display demographic distributions.
  - **KPI Cards**: Summarize metrics (e.g., avg. cost: $10,045.48).
- **Focus Areas** 🎯:
  - Treatment cost vs. recovery score 💸📈
  - Hospital performance metrics 🏥
  - Demographic and seasonal trends 👥📅

The dashboard enables intuitive data exploration. 🌟

---

## 🔍 Detailed Insights

Here’s a summary of the project’s key findings, enriched with emojis for clarity:

- **Age Group Distribution** 👶👴:
  - Senior Adults dominate (432 counts), followed by Middle Age Adults (189) and Adults (188). Infants are least represented (15). 📊
  - *Insight*: Senior Adults form the largest patient group, indicating higher healthcare needs. 🩺

- **Treatment Costs** 💸:
  - Medication averages $11.2K, Therapy $11.0K, Surgery $10.8K. Daily costs are consistent at $1.0K across all. 📈
  - *Insight*: Medication is the priciest, but uniform daily costs suggest standardized billing. 💊

- **Gender-Wise Diagnosis** 👩‍🦰👨‍🦰:
  - COVID-19: 40.10% Female, 29.70% Male, 30.20% Other (female-heavy).
  - Flu: 40.00% Other, 34.74% Male, 25.26% Female.
  - Diabetes shows slight male predominance (36.06%). 📊
  - *Insight*: Gender distribution varies; females lead in COVID-19, "Other" in Flu. 🔎

- **Blood Group Distribution** 🩺:
  - O+ (12.9%), AB+/B- (13.5% each), A+ (12.4%). Evenly distributed (10.1%–13.5%). 🍩
  - *Insight*: No dominant blood group, aiding resource planning. ✅

- **Recovery Ratings by Diagnosis & Treatment** 🌟:
  - Hypertension: 5.48 avg. (Counseling/Physical Therapy: 5.5).
  - Flu: 5.5 avg. (Physical Therapy: 5.5).
  - COVID-19: 5.0 avg. (Counseling: 5.3).
  - Counseling (5.17) outperforms Surgery (4.84). 📉
  - *Insight*: Non-invasive treatments (Counseling, Medication) yield better outcomes. 💪

- **Hospital Performance** 🏥:
  - **Riverside Hospital**: Highest recovery (5.21), lowest cost ($9,532.40). 🌟
  - **Green Valley Medical Center**: Lowest recovery (4.69), high patient load (207). ⚠️
  - Avg. patients per room: 1.20; Green Valley highest (1.27). 📊
  - *Insight*: Riverside excels in quality and cost; Green Valley needs optimization. 🔧

- **Correlation Analysis** 🔗:
  - No strong link between patient load and recovery (e.g., Dr. David Moore: 8 patients, 6.8 rating). 👩‍⚕️
  - Non-invasive treatments outperform Surgery. 📈
  - *Insight*: Doctor performance matters more than load; Counseling shines. ✅

- **Recovery by Age Group** 👥:
  - Middle Age Adults: 5.42 (highest). Infants: 4.53 (lowest).
  - U-shaped trend: Peaks at Middle Age Adults and Toddlers/Senior Adults (5.00). 📉
  - *Insight*: Middle-aged adults recover best; infants face challenges. 🩺

- **Doctor Impact** 👨‍⚕️:
  - Most doctors score 10.0 recovery rating; Barbara Wilson at 9.5. 📊
  - *Insight*: Uniformly high ratings suggest consistent doctor quality. 🌟

- **Recovery by Gender & Age** 👩‍🦰👶:
  - Adults (all genders): 5.10 (highest). Infants: 4.86–4.98 (lowest).
  - Gender differences minimal; Adults excel across the board. 📈
  - *Insight*: Age drives recovery more than gender; adults recover best. ✅

- **Cost Analysis by Hospital** 💰:
  - Cedar Sinai Clinic, Green Valley, Maple Grove: $31K (highest).
  - Riverside, Silver Oak: $29K (lowest).
  - *Insight*: Riverside offers cost efficiency; high-cost hospitals may provide specialized care. 🏥

- **Cohort Analysis** 📅:
  - 2022 cohort: High recovery, higher costs.
  - 2023 cohort: Cost-efficient but lower recovery. 📊
  - *Insight*: 2022 balances outcomes; 2023 prioritizes savings. ⚖️

- **Future Capacity** 🛏️:
  - Estimated need: 26–34 patients based on historical trends. 📈
  - *Insight*: Helps plan hospital resource allocation. 🔧

- **Recovery Trends** 🌟:
  - Toddlers score high (up to 9) for Hypertension with Medication.
  - Surgery struggles for Senior Adults and COVID-19 cases. 📉
  - *Insight*: Tailored treatments boost recovery in younger groups. 💪

---

## 🛠️ Technologies Used

- **Power BI** 📊: Visualization, DAX, and dashboards.
- **Excel/CSV** 📋: Data storage and preprocessing.
- **DAX** 🧮: Custom measures and calculations.
- **Power Query** 🔄: Data cleaning and transformation.

---

## Key Results 🥳
- Developed vibrant visualizations (bar charts, donut charts, heatmaps, KPI cards) to reveal patient demographics, treatment outcomes, and hospital performance. 📊  
- Identified critical trends, such as high recovery rates for Counseling and inefficiencies at high-load hospitals. 🎯  
- Enhanced analysis with custom DAX measures (e.g., Average Recovery Rating, Patients per Room) and interactive slicers for dynamic insights. 🖥️  

## Business Impact 🌍
This analysis delivers insights to:  
- **Optimize treatment plans** by prioritizing Counseling and Medication, improving recovery rates (up to 5.17) and cutting costs vs. Surgery ($10.8K). 💊  
- **Boost hospital efficiency** by addressing bottlenecks at Green Valley Medical Center, learning from Riverside Hospital’s low-cost, high-recovery model (5.21 rating). 🏥  
- **Enhance patient care** for vulnerable groups (e.g., Infants, Teens) with tailored treatments, increasing satisfaction and reducing readmissions. 😊  
- **Plan resources smarter** with capacity forecasts (26–34 patients), ensuring scalability without overextension. 🛏️  
