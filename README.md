# INTEGRATED-HOSPITAL-PERFORMANCE-ANALYSIS
A data-driven healthcare analytics project showcasing the use of Power BI and Excelfor real-time performance monitoring. Integrating clinical efficiency, financial metrics and patient insights into a unified decision-support dashboard.

## TABLE OF CONTENTS 
- [INTRODUCTION](#INTRODUCTION)
- [TOOLS AND TECHNOLOGIES](#TOOLS-AND-TECCHNOLOGIES)
- [METHODOLOGY](#METHODOLOGY)
- [RESULTS](#RESULTS)
- [INSIGHTS AND RECOMMENDATIONS](#INSIGHTS-AND-RECOMMENDATIONS)
- [CONCLUSION](#CONCLUSION)


## INTRODUCTION

This report presents a comprehensive, integrated analysis across three operational dashboards: Doctor's Performance Analysis, Hospital Financial Performance, and Patient Insights to deliver a holistic evaluation of the hospital's clinical efficiency, financial stability, and patient service dynamics.
In today's complex healthcare environment, a hospital's success isn't defined by a single metric but by the seamless interaction of clinical excellence and fiscal responsibility. This report moves beyond siloed data views to connect how patient volumes and treatment demands impact physician productivity, which in turn drives the hospital's overall revenue stream and collections efficiency.


## TOOLS AND TECHNOLOGIES 
- MICROSOFT POWER BI: for dashboard creation and visualization.
- MICROSOFT EXCEL:for data cleaning, transformation, and basic statistical analysis.
- MICROSOFT WORD: fr documentation and reporting.


## METHODOLOGY

The analysis is systematically structured into three core segments, one for each dashboard, ensuring detailed scrutiny of individual performance indicators, trends, and anomalies. Following the segmented analysis, a concluding section synthesizes the findings, revealing critical interdependencies: such as the link between a star doctor's high activity and the hospital's major revenue dependency, or how specific patient demographics correspond to the largest financial liabilities. This holistic approach facilitates data-driven strategic planning, targeting areas from collections management to resource allocation and clinical policy refinement. The data used in this analysis was sourced from hospital records, billing system and patient registration database. Data cleaning steps includes handling duplicates, handling missing values, and grouping related fields. The dashboards were built sing visualization tools to ensure clarity and actionable insights. KPIs were selected based on relevance to hospital operations and industry standards.

### PATIENT INSIGHTS DASHBOARD 
This segment covers valuable insights into the hospital’s patient demographics, insurance coverage, registration trends, and treatment types. The analysis helps to understand patient behavior, population segments, and service demand. 

### KEY METRICS 
- Total Registered Patients: 50 
- Average Age: 45 years
  
1. Gender Distribution by appointment: Male:130 (65%), Female:70 (35%)
2. Patient Insurance Coverage: MedCare covering 42% (84 patients), WellnessCare covering 29% (58 patients), PulseSecure covering 18% (36 patients) and HealthIndia covering 11% (22 patients).
3. Count of Patient Registrations (Monthly Trend): Registrations peaked in April (25 patients) and Lowest activity recorded in September and October.
4. Age Group Division: 
	- 30–39 years: 46 patients (23%) — largest group.
	- 40–49 years: 38 patients (19%).
	- 50–59 years: 21 patients (11%).
	- Patients aged 70+ are the smallest group (13 patients, 7%).
5. Gender Distribution: Male patients dominate at 65%, while females make up 35%.
6. Patient by Treatment Type: Chemotherapy is the most common treatment type. Followed by X-Ray, ECG, and MRI. Physiotherapy records the lowest demand.



## DOCTOR'S PERFORMANCE ANALYSIS DASHBOARD

This segment analyzes the clinical and revenue performance of the ten doctors, focusing on patient load, efficiency, and specialization demand. This provides a comprehensive analysis of doctor performance within the medical facility. It covers key performance indicators (KPIs) such as total doctors, total patients, appointment counts, patient distribution, completion rates, specializations, and revenue contributions. The goal is to evaluate efficiency, patient load distribution, and financial performance.

### KEY METRICS 
- Total Doctors: 10
- Total Patients: 50
1. Doctor Appointment Count: Top Performer is Sarah Taylor, with the highest patient appointments (approx. 23) with David Taylor and Alex Davis followimg closely behind, while the lowest appointment count is recorded by David Jones.
2. Patient Distribution by Doctor: Patient distribution is fairly spread, though Sarah Taylor (14.29%) and David Taylor (12.45%) take a larger share of the patient pool. Linda Brown and David Jones recorded the lowest shares (7.45% each).
3. Completion Rate (% of Completed Appointments): Highest completion rates are Jane Smith and David Taylor (13.04%). Other strong performers include Jane Davis, Alex Davis, Linda Wilson and Robert Davis (10.87%). Lowest completion rate is David Jones and Sarah Smith (6.52%).
4. Patients Seen by Specialization: Pediatrics holds 44.34% (largest patient base), Dermatology holds 34.91% and Oncology holds 20.75%.
5. Top Doctors by Revenue: Highest revenue generator is Sarah Taylor, followed by Jane Smith. Other notable contributors are Sarah Smith and Robert Davis with the lowest revenue is Linda Brown.



## HOSPITAL FINANCIAL DASHBOARD 

This financial performance dashboard provides insights into the hospital’s revenue generation, billing efficiency, payment status, receivables aging, and revenue distribution by doctors and payment methods. The analysis highlights both strengths and areas needing operational improvement to enhance financial stability.

### KEY METRICS 
- Total Revenue Generated: $551.25K
- Bills Paid: 31%
- Failed Bills: 35%
- Pending Bills: 33%
- Average Revenue per Patient: ₦11.02K
1. Revenue Trend: Revenue fluctuated significantly across months, peaking around May/June before dropping again in later months.The inconsistent revenue pattern indicates seasonality or operational inefficiencies that may need addressing.
2. Revenue by Payment Status: Paid bills amounts to $173,424. Pending amounts to $184,612 and Failed amounts to $193,212.
3. Receivables Aging: Highest Outstanding Group is the patients aged 30–39 with $166,226. The 40–49 group also contributes a large share of pending receivables. Older age groups (60+) show smaller but significant outstanding balances.
4. Top Doctors by Revenue: Sarah Taylor is the top revenue generator, followed by Sarah Smith, Linda Wilson, and Robert Davis.
5. Revenue by Payment Method: Credit Card dominates payment methods, followed by Insurance and Cash.




## RESULTS

### PATIENTS ANALYSIS SEGMENT 
![PATIENT DASHBOARD](https://github.com/Spectre-Ghost-dev/INTEGRATED-HOSPITAL-PERFORMANCE-ANALYSIS-/blob/main/PATIENT%20INSIGHTS.png)
The overall analysis of the patients shows the following results:
1. There is a male dominated population, with a middle-aged average profile.
2. Medcare Insurance leads as the preferred service provider, while HealthIndia has the least adoption. This may indicate stronger trust or better service agreements with Medcare.
3. Fluctuations in registration suggest seasonal or campaign-driven variations in patient inflow.
4. The data shows a strong concentration of patients in the 30-49 years age bracket, which is consistent with thee average age.
5. The imbalance I'm more the gender distribution may point to differences in health-seeking behaviour or hospital accessibility.
6. High demand in chemotherapy indicates that Oncology is a critical area for the hospital.
   

### DOCTORS PERFORMANCE ANALYSIS SEGMENT 
![DOCTORS PERFORMANCE DASHBOARD](https://github.com/Spectre-Ghost-dev/INTEGRATED-HOSPITAL-PERFORMANCE-ANALYSIS-/blob/main/DOCTORS%20PERFORMANCE.png)

The following results were derived from the analysis:
1. There's an uneven patient distribution across doctors, with a few doctors handling the bulk of appointments.
2. The wide range highlights opportunities for targeted improvement, particularly for doctors with completion rate below 8%.
3. The facimay need to balance the patient allocation to avoid overburdening certain doctors while underutilising others.


### HOSPITAL FINANCIAL ANALYSIS SEGMENT 
![HOSPITAL FINANCIAL DASHBOARD](https://github.com/Spectre-Ghost-dev/INTEGRATED-HOSPITAL-PERFORMANCE-ANALYSIS-/blob/main/HOSPITAL%20FINANCE.png)


Below are the results gotten from the analysis of the hospital's finance:
While the overall revenue is substantial, collection efficiency is low, with less than one-third of bills successfully paid.
The inconsistent revenue pattern indicates seasonality or operational inefficiencies that may need addressing.
There's an indication that middle-aged (30-49 years ) are most likely to delay or fail payments.
Heavy reliance on credit cards suggests a need to ensure robust payment gateway reliability.

## INSIGHTS AND RECOMMENDATIONS 

The following insights and recommendations are provided for each of the segmented analysis:

### PATIENTS ANALYSIS SEGMENT 

1. Insurance Partnership: Strengthen collaboration with Medcare while expanding incentives to encourage adoption of Wellness care, Pulse care, and HealthIndia.
2. Patient Acquisition: Investigat why registrations drop sharply in September - October; consider health campaigns or awareness program 
3. Target Age Brackets: Focus marketing and preventive health programs on the 30-49 demographic, which forms the largest patient base.
4. Gender Balance: Explore strategies to engage more female patients e.g., women's health programs or specialized services.


### DOCTORS ANALYSIS SEGMENT 

1. Patient Load Balancing: Reassign patients more evenly to avoid over-dependence on top doctors Ike Sarah Taylor and Jane Smith
2. Performance Coaching: Provide additional support to low completion rate doctors.
3. Revenue Strategy: Incentivize doctors with lower patient inflow to improve engagement and potentially increase revenue.
4. Specialization Focus: Given Pediatrics' high demand, the facility may expand pediatric resources, while developing strategies to increase flow for Oncology.

### HOSPITAL FINANCIAL ANALYSIS SEGMENT

1. Improve Bill Collection Efficiency: With only 31% bills paid, immediate strategies are needed to follow up on pending and failed payments.
2. Doctor Incentives: Recognise high-revenue doctors while motivating others to improve contribution.
3. Revenue Stabilization: Investigate revenue fluctuations across months to identified seasonal trends and optimize operations during low months.
4. Payment Method Diversification: While credit cards usage is high, expanding cashless alternatives and insurance partnerships could balance revenue inflow.


## CONCLUSION 

The hospital demonstrates strong financial potential, with consistent revenue generation and a robust operational structure. However, inefficiencies in bill collection and the high rate of failed or pending payments present significant risks to long-term financial health. Strengthening the billing system, improving receivables management, and streamlining payment processes will not only enhance cash flow but also elevate patient trust and satisfaction.

Patient demographics reveal a predominantly middle-aged, male, and MedCare-insured population. While oncology services perform strongly, physiotherapy and other underutilized departments indicate opportunities for better resource distribution. Efforts to balance gender representation, improve seasonal registration stability, and diversify insurance participation will drive more inclusive and sustainable patient engagement.

From a performance standpoint, certain doctors and specializations excel in patient count and revenue generation, while others remain underleveraged. By addressing disparities in workload, boosting completion rates, and aligning resources with patient demand, the hospital can achieve greater operational efficiency, equitable service delivery, and improved health outcomes overall.
