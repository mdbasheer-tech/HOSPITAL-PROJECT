![image alt]()
Hospital Data Analytics Power BI Dashboard Project
Overview
This project presents a complete data analytics workflow applied to hospital operations data. Using Excel for data preparation and Power BI for visualization, the project delivers an interactive dashboard that highlights patient flow, diagnosis trends, bed occupancy, doctor feedback, and financial performance. The goal is to demonstrate practical skills in data cleaning, modeling, and visualization while producing a portfolio-ready deliverable.
Dataset Structure
The dataset includes the following columns:
- Patient_ID – Unique identifier for each patient
- Admit_Date / Discharge_Date – Hospitalization timeline
- Diagnosis – Illness type (e.g., Viral Infection, Flu, Malaria, Typhoid, Pneumonia, Fracture)
- Bed_Occupancy – Ward type (Private, General, ICU)
- Test – Medical tests conducted
- Doctor – Attending physician
- Followup_Date – Scheduled post-discharge follow-up
- Feedback – Patient feedback volume
- Billing Amount – Total billing per patient
- Health Insurance Amount – Insurance coverage per patient
Data Preparation
- Cleaned and standardized patient records
- Converted date fields into consistent formats
- Aggregated diagnosis categories for trend analysis
- Created measures for billing vs. insurance comparisons
- Ensured compatibility with Power BI filters (Patient_ID, Date Range, Diagnosis)
Dashboard Components
- Patient Timeline
- Admit, discharge, and follow-up tracking
- Example: Patient admitted on 05-Dec-22, discharged on 12-Jan-23, follow-up on 15-Jan-23
- Bed Occupancy
- Private: ~3.5K
- General: ~2.2K
- ICU: ~1.2K
- Feedback by Doctor
- Seven doctors with ~1.02K feedback each (≈14.3%)
- Balanced distribution across physicians
- Diagnosis Trends
- Viral Infection: 2.00K
- Flu: 1.72K
- Malaria: 1.43K
- Typhoid: 1.15K
- Pneumonia: 0.57K
- Fracture: 0.29K
- Financial Insights
- Billing vs. Insurance amounts by diagnosis
- Both metrics show a downward trend from Viral Infection to Fracture
- Example: Billing peaked at ~₹60M for Viral Infection, declining sharply for less frequent diagnoses
Key Insights
- Viral infections and flu dominate patient volumes
- Private wards account for the highest occupancy
- Feedback distribution suggests consistent patient engagement across doctors
- Billing amounts consistently exceed insurance coverage, highlighting affordability gaps
Deliverables
- Cleaned dataset in Excel
- Power BI data model with relationships and measures
- Interactive dashboard with filters and visualizations
- Documentation summarizing workflow, insights, and outcomes
Value
This project demonstrates:
- Practical application of data analytics in healthcare
- Proficiency in Excel data preparation and Power BI visualization
- Ability to generate actionable insights from operational data
- A portfolio-ready dashboard suitable for resumes and professional presentations
