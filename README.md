# PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT

## Project Overview
This report outlines the steps taken to identify patients who at high health risk based on their vitals and medical history in order to prioritize health care, reduce emergencies and improve patient outcomes.

## Table of Content
- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Tasks](#tasks)
- [Deliverables](#deliverables)
- [Datasets](#datasets)
- [Methodology](#Methodology)
- [Answer to Questions](#answer-to-questions)
- [Recommendations](summary-and-recommendations)

## Tools Used
Microsoft Power BI
Microsoft Excel

## Tasks
1.	Clean and merge datasets
2.	Define health risk thresholds (clearly documented)
3.	Assign risk levels to patients
4.	Create visual summaries:
  ○	Risk by age group
  ○	Risk of chronic condition
5.	Write actionable recommendations

## Deliverables 
●	Cleaned dataset
●	Risk classification table
●	Dashboard or charts
●	2–3 pages analytical report

## 1.	Clean and merge datasets
I copied the patients and vitals dataset from the link provided https://docs.google.com/document/d/1WRah5zfdE4vy5bz3XOFIBx_0YjWxtL_BYkmxKOBxSmo/edit?usp=sharing and pasted it on Microsoft Excel worksheet, after which I saved the documents. Then I opened my Microsoft Power BI to get the patients and vitals datasets I saved from Ms. Excel, it loaded to the power query where I was able to clean, transform and merge both datasets.

## Datasets
![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/Patients%20Dataset.jpg)
![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/Vitals%20Dataset.jpg)

## Merged Dataset
![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/Merged%20Dataset.jpg)

## 2.	Patient Health Risk Threshold
According to the American Heart Association,  

**Blood Pressure**
-	Normal: <120/ <80 mmhg
-	Elevated: 120–139 / 80–89 mmhg
-	High Risk: ≥140 / ≥90 mmhg
  
**Glucose Level**
-	Normal: <100 mg/dl
-	Prediabetes: 100–125 mg/dl
-	High Risk: ≥126 mg/dl
  
**Heart Rate**
-	Normal: 60–100 bpm
-	High Risk: >100 or <60 bpm

Patient is at high health risk if patient has chronic condition and abnormal vitals i.e BP greater or equal to 140/90mmhg or glucose level greater than or equal to 126mg/dl.
Patient is at medium health risk if patient has slightly abnormal vitals (prehypertension or prediabetes).
Patient is at low health risk if all vitals are normal and no chronic conditions. 

## 3.	Risk Classification Table
To get the patient’s risk classification table, I had to create a column for risk level and to do this I clicked on my merged dataset (PatientHealthRisk), I used the formula below to get the risk levels. 
Then I clicked on table pane from the visual gallery on the home page. The I inserted the patient ID, Age, Gender, Chronic condition, Systolic BP, Diastolic BP, Heart Rate, Glucose Level and Risk Level into the columns. 

![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/Risk%20Level.jpg)
![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/Patient's%20Risk%20Classification%20Table.jpg)

## 4.	To create visual summaries.
I created a dashboard containing Total number of patients, high, medium and low risk patients, a chart showing risk levels by age group, pie chart showing risk level by chronic conditions, slicers containing chronic conditions, gender, location and risk level. The formulas I used is as seen below. 
![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/Patient%20Health%20Risk%20Analysis%20Dashboard.jpg)
![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/High%20Risk%20Patients.jpg)
![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/Low%20Risk%20Patients.jpg)

## Answer to Questions
**Which patients have abnormal vitals?** 
Ans: From the table it can be deduced that patients with patients ID P001, P002, P004, P005, P007 have abnormal vitals.
**Which age groups show higher health risks?**
Ans: From the column charts, patient with age groups 40 years and above show significantly higher health risks as compared to patients below 40 years. 
**What chronic conditions are most associated with high-risk vitals?**
Ans: From the pie chart above Hypertension, Diabetes and Heart disease are associated with high-risk vitals.
**How many patients fall into each risk category?**
Risk Level	Count
High Risk	   5
Medium Risk  0
Low Risk	   2

## Recommendations
**For High Health Risk patients**
-- I’d advise Remote health to check their blood pressure and glucose level regularly preferably on a weekly basis.
-- Pharmacists working at remote health should review their medications and check for any medication related problem.
-- They should be advised on lifestyle modification such as exercise, DASH diet (Dietary Approach to Stop Hypertension), reduction in salt intake, alcohol avoidance, stress reduction.
-- Alerts should be sent to the health care team when vitals exceed thresholds.

**Low Health Risk Patients**
-- Adopt life style modification early
-- They should be educated on their health, the risk factors that can cause the chronic conditions.
-- They should be encouraged on quarterly checkups of their blood pressure and glucose levels.





