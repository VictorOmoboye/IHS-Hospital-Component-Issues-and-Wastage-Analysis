# NHS HOSPITAL COMPONENT ISSUES & WASTAGE ANALYSIS 
## Leveraging Power BI to Optimize Blood Component Management by Uncovering Insights into Issues, Wastage, and Inventory Management
![image](https://github.com/user-attachments/assets/c4f0e9b5-7ab5-4902-ba68-374c94a38615)

## INTRODUCTION
The **NHS Blood Stocks Management Scheme (BSMS)** aims to enhance blood inventory management across the supply chain. This project utilizes Power BI to analyze hospital component issues and wastage trends, focusing on Red Blood Cells, Platelets, and Frozen Plasma. Key insights reveal strong issue-wastage correlations, seasonal patterns, and major wastage causes like Time Expiry (TIMEX). The findings offer data-driven recommendations to optimize inventory management and minimize wastage for NHSBT BSMS.
![image](https://github.com/user-attachments/assets/b256cb67-793a-4229-94ab-b1581ecf4cad)

## PROBLEM STATEMENT
- Hospitals face challenges in managing blood component inventory, leading to high wastage and supply inefficiencies.
## AIM OF THE PROJECT
- **Analyze Trends:** Identify patterns in hospital component issues and wastage using Power BI to understand their correlation and root causes.
- **Optimize Inventory Management:** Provide data-driven insights to reduce wastage, especially from Time Expiry (TIMEX), and improve blood supply efficiency.
- **Enhance Decision-Making:** Support NHSBT BSMS with strategic recommendations for better forecasting, allocation, and utilization of blood components.

## METHODOLOGY 
- **Business Understanding:** I defined project objectives to analyze trends in NHS hospital
component issues and wastage.
- **Data Understanding:** I explored the dataset to identify key features and
relationships for analysis.

- **ETL Process:** I extracted, transformed, and loaded the data into Power BI for
compatibility and analysis.

- **Data Modeling:** I created relationships between fact and dimension tables for
structured analysis.

- **Analysis & Visualization:** I used Power BI to generate trendline charts and
visualizations, uncovering correlations and patterns in issues and wastage.

## MODELLING
The data modeling for this project follows a star schema approach, where the **Fact Table** (containing hospital component issues and wastage records) is connected to multiple **Dimension Tables** to ensure efficient analysis. The **Fact Table** includes key metrics such as issue counts, wastage counts, product group names, and blood group names. It is linked to **Dimension Tables** like **Blood Group (O-, A+, etc.), Calender (Year, Quarter, Month), and Wastage Codes (TIMEX, TTMH, etc.)** through unique identifiers. This relational structure allows for seamless trend analysis, comparisons across different categories, and deeper insights into the root causes of wastage and inventory inefficiencies.

![image](https://github.com/user-attachments/assets/2e3e66b0-be62-4eff-affd-e1f42defe90c)

## VIZUALIZATION
- **Line Chart**
- **Bar Chart**

## Data Analysis
### Line Chart
This chart reveals a strong correlation between hospital component issues and wastage, with both following similar yearly trends. Whenever component issues increase, wastage also rises proportionally. Notably, 2023 recorded the highest levels of both issues and wastage compared to previous years (2022 and 2023), indicating a need for improved inventory management strategies.
![image](https://github.com/user-attachments/assets/fc628671-949c-4a94-99fe-d5af12a8fb4d)

A quarterly analysis of the correlation between component issues and wastage reveals distinct trends. In 2022, component issues peaked in Q2 before declining in Q3, while wastage followed a similar downward trend. However, in 2023, wastage exhibited a sharp upward trend from Q1 to Q3, surpassing component issues, particularly between Q2 and Q3. A deeper dive into monthly patterns suggests seasonality, with high component issues and low wastage observed in May (Q2) and August (Q3) of 2022. Conversely, in 2023, wastage peaked in September (Q3) while component issues remained relatively low.
![image](https://github.com/user-attachments/assets/b83086ad-96a1-4f34-9673-f2a15258c3d6)

An analysis of component issue trends by product group reveals that Red Blood Cell (RBC) issues remained consistently high throughout the three-year period (2022–2024), significantly surpassing other components. Platelet (PLT) issues ranked second, while Pooled Cryo recorded the lowest issue volumes across all years.
![image](https://github.com/user-attachments/assets/7e191e09-b28a-4942-b73f-749e5f626daf)

An analysis of component issue trends by product group reveals display that Platelet wastage exhibited a consistent upward trend from Q4 2022 to Q4 2023, while component issues fluctuated across the quarters.
![image](https://github.com/user-attachments/assets/e0d83fc2-991c-48d9-895d-62ff1fa3ddcd)

An analysis of component issue trends by product group reveals Adult FFP wastage spiked in Q2 2023, while component issues followed a downward trend across the quarters.
![image](https://github.com/user-attachments/assets/cd0ef693-f6b6-431f-a2e3-41423124b845)

A Negative Blood Group Issues peaked in Q1 2023 and declined through Q2 and Q3, while wastage surged in Q2 before declining in Q3. This indicates a potential mismatch between demand and supply, highlighting the need for improved forecasting and inventory adjustments to minimize wastage.
![image](https://github.com/user-attachments/assets/7abe224c-240e-41d4-920e-aeeff3e15a3d)

O Negative Blood Group Issues declined in Q3 2022, while wastage peaked in Q1–Q2 2023 before declining in Q3. This trend suggests potential inefficiencies in stock utilization, emphasizing the need for optimized allocation strategies to reduce wastage while ensuring adequate supply.
![image](https://github.com/user-attachments/assets/56b9f349-b366-4b32-9815-7fcaaaf6caec)

Red Cells have the highest units in both Issues (76.28%) and Wastage (44.78%). Platelets and Adult FFP follow in respective distributions, with Platelets having more Issues and Adult FFP having more Wastage. This highlights the need for targeted inventory controls, especially for Red Cells, to minimize wastage while maintaining adequate supply levels.
![image](https://github.com/user-attachments/assets/ce732bbe-53e5-4187-8c10-fbc689db302d)

Root Cause of Wastage: Time Expiry (TIMEX) is the primary contributor, responsible for 31% of total wastage units, followed by TTMH at 15%, highlighting the need for improved stock rotation and demand forecasting strategies.
![image](https://github.com/user-attachments/assets/7d8f0e85-88ca-43d7-8548-d265d4c9e786)


## RECOMMENDATION
- **Target Top Wastage Causes:** Focus on minimizing the top 10 wastage drivers, especially Time Expiry (TIMEX), which contributes the most to wastage.

- **Optimize RBC Management:** Monitor and manage Red Blood Cell (RBC) stocks carefully due to their consistently high issues and wastage volumes.

- **Adjust for Seasonal Trends:** Align inventory strategies with seasonal and quarterly trends to prevent overstocking during low-demand periods and shortages during peak wastage times (e.g., Q2–Q3 2023).

- **Blood Group-Specific Allocation:** Tailor inventory levels for key blood groups like O Negative and A Negative to address fluctuations in issues and wastage effectively.

- **Enhanced Monitoring of Platelets and Frozen Components:** Closely track and address rising wastage trends in Platelets and Adult FFP, particularly the surges observed in Q1–Q3 2023.








# Thank you for reading. Still under contruction, Check back later...... 
