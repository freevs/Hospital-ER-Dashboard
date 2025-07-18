# Hospital Emergency Room Dashboard

![Alt Text](https://thumbs.dreamstime.com/b/emergency-room-entrance-glass-door-background-hospital-activity-modern-features-bold-red-lettering-blurred-357044368.jpg)

## Goal
To enhance operational efficiency and provide actionable insights into emergency room performance by analyzing patient flow, wait times, admission rates, and satisfaction metrics using Power BI. The dashboard aims to help hospital administrators and staff make data-driven decisions to reduce delays, optimize resource allocation, and improve patient care

## Steps Performed
**Data Acquisition & Understanding**
* Utilized  dataset from Kaggle containing patient demographics, admission details, department referrals, satisfaction scores, wait times, and outcomes from April 2023 to October 2024.
* Explored the dataset structure to understand feature definitions and the context of ER operations.

**Data Cleaning & Wrangling**
* Standardized data fields (e.g., gender), addressed missing or inconsistent values, and created new columns such as full name for clarity and analysis readiness.
* Extracted key temporal features (month, year) from date fields and structured the data to enable time-based insights.
* Evaluated data quality by reviewing distributions and handling anomalies as needed.

**EDA & Dasboard Creation**
* Developed calculated columns and DAX measures to quantify key metrics such as average ER wait time, patient admission rates, and satisfaction scores
* Created additional features to facilitate breakdown by demographic and service attributes.
* Built an interactive dashboard in Power BI, enabling real-time exploration of ER performance, wait times, patient satisfaction, department referrals, and operational bottlenecks.
* Incorporated dynamic filters, charts, and KPIs to allow users to analyze trends by month, demographic segment, referral department, and more.

## Insights
* Average Wait Time: 35 minutes (monthly) and 35.3 minutes (consolidated), with only about 59% of patients seen within the 30-minute target.
* Admissions: Almost an even split—50% admitted, 50% not admitted. Indicates potential for optimizing triage and patient flow.
* Department Referrals: Most patients did not require referrals; among referred, general practice and orthopedics were the most common.
* Gender: Slightly more male than female patients; close to even.
* Age: Patient load spread across all age groups, highest in 30–39 and 20–29 brackets.
* Race: White and African American patients represented the largest groups; notable number declined to specify.
* Satisfaction Score: Patient satisfaction averages around 5/10, highlighting need for service improvements.
* Peak Load Times: Highest patient inflow during late morning and early afternoon hours and at the start/end of the week.
* Bottlenecks: Significant number of patients miss the 30-minute wait time target, especially during peak hours.

## Recommendations
* Reduce Average Wait Times: Increase staffing or streamline triage processes during peak hours, as only about 59% of patients are seen within the 30-minute target and average wait times hover around 35 minute.
  
## Dasboard

![Alt Text](https://github.com/freevs/Hospital-ER-Dashboard/blob/main/images/Monthly%20View.png)

![Alt Text](https://github.com/freevs/Hospital-ER-Dashboard/blob/main/images/Consolidated%20View.png)

![Alt Text](https://github.com/freevs/Hospital-ER-Dashboard/blob/main/images/Patient%20Details.png)


