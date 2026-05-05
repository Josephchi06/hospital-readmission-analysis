# 🏥 Hospital 30-Day Readmission Analysis

##  Overview
This project analyzes 30-day hospital readmissions using over 100,000 patient encounters to identify key factors influencing patient return rates. The analysis focuses on understanding how patient demographics, hospital stay characteristics, and prior admission history contribute to readmission risk, with the aim of improving patient care and identifying high-risk groups.

----

## Business Problem
This project aims to analyze patient, treatment, and hospital factors that contribute to hospital readmissions, with the goal of identifying patterns that can improve patient outcomes and support more efficient healthcare resource utilization.

----

## 📊 Dataset
The dataset used for this analysis is the **Diabetes 130-US Hospitals dataset**, which contains over 100,000 patient encounters collected from multiple hospitals in the United States between 1999 and 2008.

- Records: 101,766  
- Features: 50 columns  

🔗 Dataset Link: https://www.kaggle.com/datasets/sulphatet/diabetes-130us-hospitals-for-years-19992008

### Key Variables
- Age  
- Gender  
- Time in hospital  
- Number of inpatient visits  
- Diagnosis codes  
- Readmission status

----

  ## Business Questions
The analysis focuses on answering the following key questions:

1. Which age groups are most likely to be readmitted?  
2. Does length of stay influence readmission rates?  
3. How does prior inpatient history affect the likelihood of readmission?  
4. Which medical conditions are associated with higher readmission rates?


----

  ## Key Metrics
The following key metrics were used to evaluate hospital readmissions:

- **Total Patients (Encounters):** 101,766  
- **30-Day Readmissions:** 11,356  
- **Readmission Rate:** 11.16%


-----

  
##  Analysis & Insights

### Readmission by Age Category
- Youth patients have the highest readmission rate (~12.2%)  
- Teenagers show the lowest risk (~5.0%)  
- Adults and seniors maintain moderate readmission levels  

 Insight: Younger adults represent a higher-risk group, possibly due to lifestyle factors or lower adherence to treatment plans.

---

### Readmission by Stay Category
- Long stay patients (~13.1%) have higher readmission rates than short stay patients (~10.4%)  

Insight: Length of stay reflects patient complexity rather than discharge timing, with more severe cases being more likely to return.

---

### Readmission by Inpatient Category
- First-time patients: ~8.4%  
- Low frequency: ~14.2%  
- Medium frequency: ~22.8%  
- High frequency: ~39.8%  

 Insight: Prior inpatient history is the strongest predictor of readmission, with high-frequency patients showing significantly elevated risk.

---

### Readmission by Medical Condition
- Diabetes cases have the highest readmission rate (~13.0%)  
- Injury cases follow (~12.2%)  
- Other conditions show slightly lower rates  

 Insight: Medical condition contributes to readmission risk, with diabetes patients showing the highest likelihood of return, though differences across conditions remain moderate compared to patient history.

 ----
 ## 📊 Dashboard
![Dashboard](hospital_dashboard.png)

