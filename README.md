# Big-Data-Analysis-of-Trucking-Risk-Factors-Using-Spark-APIs
A Spark-powered big data project that analyzes risk factors for truck drivers and fleets using Hive, Tableau, and R integration. Includes location-based risk insights, driver behavior analysis, and vehicle model comparisons.

## Project Introduction
Trucking accidents remain a serious concern across the United States. This project simulates a real-world scenario for Az National Trucking (ANT), where we act as Fleet Managers aiming to proactively identify high-risk drivers and vehicles. Leveraging the power of Apache Spark, Hive, and Tableau, we perform in-depth analytics to uncover behavioral risk patterns and geographical hotspots that contribute to road safety risks.

## Objectives

- Identify drivers with risk factors ≥ 7.0 to alert corporate leadership and insurers.
- Analyze trucking data to assess driver behavior, truck model performance, and location-based risk patterns.
- Use geolocation data and telematics insights to improve compliance with FMCSA regulations.
- Provide visual dashboards for better fleet decision-making.

## Tech Stack

- Apache Spark (via Databricks) -	Big data transformation and processing
- HDFS	- Distributed data storage
- Hive	- Data warehousing and querying
- Tableau	Dashboard - creation and data visualization
- R - Integration	Regression analysis within Tableau
- Cloudera Hadoop -	Infrastructure for big data storage and processing


<br><br>


## Project Architecture

[Raw CSV] → [HDFS] → [Spark Transformations] → [Hive Tables] → [Tableau Dashboards] + [R Server]


<br><br>


## Workflow Diagram

![image](https://github.com/user-attachments/assets/241a2476-06d7-4b7c-ba8a-fa3e08b19d8f)



<br><br>


## Key Analyses & Dashboards

### 1. Drivers with Top Risk Factors

![image](https://github.com/user-attachments/assets/3a3b7a17-879d-4936-b838-740e6dd9b7db)


- Identifies the top 10 drivers whose behavior indicates elevated risk.
- Example: Driver A73 has the highest risk score across the fleet.


<br><br>


### 2. Risk Factors by Truck Model

![image](https://github.com/user-attachments/assets/0a4ebfca-b0b7-480c-8f82-944184257323)


- Shows truck models like Oshkosh and Crane with consistently high risk.
- Suggests that vehicle type plays a role beyond just driver behavior.


<br><br>


### 3. Geographical Risk Analysis

![image](https://github.com/user-attachments/assets/ad305445-b414-466c-980f-9818cd39e8b7)


- Highlights high-risk cities across California using choropleth maps.
- Cities like Occidental and Mariposa exhibit the highest risk levels.


<br><br>


### 4. Event Frequency by City

![image](https://github.com/user-attachments/assets/8a2c1de2-4261-4861-b1d6-e13ee598bfc7)


- Maps the density of abnormal events (overspeeding, tailgating, etc.)
- Santa Rosa and Willits emerge as hotspots for frequent violations.


<br><br>


### 5. Regression Analysis with R
- Performed predictive modeling to understand factors influencing risk levels.
- Helps forecast future risk-prone areas or vehicle segments.


<br><br>


## Conclusion

Through this project, we established a clear pipeline for:

Identifying behavioral and mechanical risk contributors.
Enabling data-driven safety interventions.
Reducing insurance costs and improving regulatory compliance.

Replacing high-risk truck models and training drivers in high-risk areas are two key takeaways that can significantly improve fleet safety.
