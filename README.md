# 🎯 NFSA Monthly Allocation Transaction and Foodgrain Distribution Dashboard
Interactive Power BI dashboard analyzing NFSA foodgrain allocation, transactions, distribution efficiency, Aadhaar authentication, and ePoS adoption across Indian states.

## 🚩Objective
The objective of this project is to analyse and visualize the monthly allocation, transactions, and foodgrain distribution under the National Food Security Act (NFSA) across Indian states and union territories. The dashboard aims to monitor the efficiency of foodgrain allocation and distribution, evaluate state-wise performance, identify distribution gaps, and provide actionable insights that support transparent and data-driven decision-making for the Public Distribution System (PDS).

## 📖 Data Source
Dataset Original Source Link: https://ndap.niti.gov.in/dataset/7115

Timeline: 2017 - 2024

## ❔Problem Statement
The National Food Security Act (NFSA) aims to ensure food security by providing subsidized foodgrains to eligible beneficiaries through the Public Distribution System (PDS). However, monitoring the efficiency of foodgrain allocation, distribution, and beneficiary transactions across different states and over multiple months is challenging due to the large volume of data and the lack of a centralized analytical view.

Without an interactive reporting system, it is difficult to identify disparities between allocated and distributed foodgrains, evaluate the adoption of digital distribution methods such as ePoS and Aadhaar authentication, detect underperforming regions, and monitor overall distribution efficiency. This limits the ability of policymakers and administrators to make timely, data-driven decisions.

## 📦 Attributes

| Attribute Name | Description |
| --- | --- |
| Source Year	| The original year in which the data was published or collected from the NFSA/PDS source. |
| State Name | Name of the Indian State or Union Territory where the foodgrain allocation and distribution activities took place.|
| Region Name	| Geographical region of the state (e.g., North, South, East, West, North-East, Central) used for regional analysis. |
| Source Month | The original month from the source dataset representing the reporting period.|
| Food grains allocated	| Total quantity of foodgrains allocated to the state under the National Food Security Act (NFSA) for the specified month, usually measured in metric tonnes (MT).|
| Ration cards issued	| Total number of ration cards issued to eligible beneficiaries in the state under the Public Distribution System (PDS).|
| Transaction for ration cards | Total number of ration card transactions recorded during the reporting month.|
| Aadhaar authenticated Transactions | Number of ration card transactions successfully authenticated using Aadhaar-based biometric verification.|
| Aadhaar Authenticated Transaction (%) |	Percentage of total ration card transactions that were authenticated through Aadhaar. It indicates the adoption of digital authentication.|
| ePoS (Electronic Point of Sale system) distribution of food grains |	Quantity of foodgrains distributed through Electronic Point of Sale (ePoS) devices, enabling digital and transparent beneficiary verification.|
| Manual distribution of food grains |	Quantity of foodgrains distributed manually without using ePoS devices, generally due to connectivity or operational constraints.|
| Distribution of food grains	| Total quantity of foodgrains distributed to beneficiaries during the reporting month, including both ePoS and manual distribution.|
| YearCode | Numeric code representing the reporting year, used for sorting and time-based analysis (e.g., 2024, 2025).|
| Year | Reporting year of the transaction and distribution data.|
| MonthCode |	Numeric representation of the month (1 = January, 2 = February, ..., 12 = December) used for chronological sorting in reports.|
| Month	| Name of the reporting month (e.g., January, February, March) used for trend analysis and visualization.|

## 🧰 Tools & Technologies

### Microsoft Excel 
•	Data cleaning 
•	Handling missing values 
•	Data preprocessing 
•	Initial data analysis 

### Power Query 
•	Data transformation 
•	Data type formatting 
•	Removing duplicates 
•	Creating calculated columns 

### Power BI 
•	Data modeling 
•	DAX (Data Analysis Expressions) calculations 
•	Dashboard creation 
•	Interactive visualizations 

## 📋 Data Pre-Processing (Excel / Power Query)

## Excel: 
Data Cleaning and Transformation – Changed column header name, Standardized format, Applied Filters.

## Power BI: (Power Query): 
Removed columns, capitalized each word, re-ordered columns, changed type, used DAX for Calculated Column and Measures, used Visuals for Dashboard.

## ** Calculated Measures 
Total Allocation, Total Distribution, Total Transactions, Aadhaar Transactions, Distribution Efficiency (%), Aadhaar Authentication Rate (%), ePoS Usage (%), Manual Distribution (%), Average Allocation per State, Average Transactions

## ** Calculated Columns
Distribution Gap, Distribution Status, Aadhaar Performance, Year-Month, Quarter, Distribution Mode

## 📊 Dashboard Visual Descriptions (Power BI)

### a)	Slicer – Year Filter

Purpose: The Year slicer allows users to filter the dashboard by a specific reporting year. All visuals update automatically based on the selected year.

Selected Year: All (2017–2024) 

Insight: The dashboard currently displays consolidated data for all available years.

### b)	Line Chart – Total Distribution by Year-Month

Purpose: The Line Chart illustrates the monthly trend in foodgrain distribution across the selected time period, helping identify increases, decreases, and seasonal patterns.

Insight: Distribution remained relatively stable at approximately 8 Million MT during most of 2023. 
A decline is observed in early 2024, indicating lower foodgrain distribution during the selected months.

### c)	Clustered Bar Chart – Distribution of Foodgrains by State

Purpose: The Clustered Bar Chart ranks states according to the quantity of foodgrains distributed.

Insight:
•	Uttar Pradesh has the highest foodgrain distribution. 
•	Bihar and Maharashtra are the second and third highest contributors.

### d)	Treemap – State-wise Ration Cards Issued

Purpose: The Treemap displays the proportion of ration cards issued across states. Larger rectangles indicate states with more beneficiaries.

Insight:
•	West Bengal and Uttar Pradesh occupy the largest areas, indicating a high number of ration card holders. 
•	States such as Maharashtra, Bihar, and Tamil Nadu also have substantial beneficiary populations.

### e)	Donut Chart – ePoS vs Manual Foodgrain Distribution

Purpose:  The Donut Chart compares the quantity of foodgrains distributed through Electronic Point of Sale (ePoS) devices versus manual distribution.

Insight:
•	Nearly 89% of foodgrain distribution is carried out through ePoS, indicating strong adoption of digital distribution systems. 
•	Only 11% of distribution is manual, suggesting improved transparency and digital governance. 

### f)	Gauge Chart – Distribution Efficiency

Purpose: The Gauge Chart measures the percentage of allocated foodgrains that were successfully distributed.

Insight:
•	Approximately 87.48% of allocated foodgrains have been distributed. 
•	The remaining 12.52% represents the distribution gap, highlighting an opportunity to improve delivery efficiency.

## Conclusion

•	Developed an interactive Power BI dashboard to analyse NFSA monthly allocation, transactions, and foodgrain distribution. 

•	Monitored state-wise and monthly distribution trends using interactive visualizations. 

•	Evaluated the efficiency of foodgrain distribution by comparing allocation with actual distribution. 

•	Analysed the adoption of Aadhaar authentication and ePoS-based distribution across states. 

•	Identified top-performing states based on foodgrain distribution and ration card issuance. 

•	Used Power Query and DAX to clean, transform, and model the data effectively. 

•	Implemented KPIs, charts, maps, and slicers to provide meaningful and interactive insights. 

•	Enabled data-driven decision-making by presenting key performance metrics in a user-friendly dashboard. 

•	Demonstrated how Power BI can improve transparency, monitoring, and reporting of the Public Distribution System (PDS). 

•	The project highlights the value of Business Intelligence in supporting efficient implementation of the National Food Security Act (NFSA).

<img width="1367" height="778" alt="Screenshot 2026-07-24 000715" src="https://github.com/user-attachments/assets/52f7cc34-c7a9-4762-bd0b-87188e4df5a0" />
