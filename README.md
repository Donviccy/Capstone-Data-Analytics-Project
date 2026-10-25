# Capstone-Data-Analytics-Project
Logistics Operations and Fleet Performance Analytics
# Overview
This project examines how logistics and fleet data can be organised and analysed to support operational performance monitoring and evidence-based decision-making using an interactive dashboard. 
The project presents a 3-year operational analysis covering 85,410 loads using a relational database structure covering trucks, drivers, trailers, customers, facilities, routes, loads, trips, fuel purchases, maintenance records, delivery events, safety incidents, and aggregated performance metrics.
Interactive filters allow users to examine results by booking type and customer type, while the navigation tabs provide access to different analytical sections.
The objective is to demonstrate how structured data can be used to investigate delivery reliability, fleet utilisation, fuel efficiency, operating costs, driver performance, and customer service.
The project demonstrates how data analytics and visualisation can support operational monitoring, identify areas requiring further investigation, and inform evidence-based decisions in logistics and supply chain management.
# Objectives
The project aims to:
I. Evaluate revenue and profitability across the logistics operation.
II. Examine revenue distribution by booking type, customer and transport lane.
III. Assess service performance using on-time delivery and pickup indicators.
IV. Analyse driver performance, idle time, and fuel-efficiency metrics.
V. Monitor fleet availability, maintenance expenditure, and vehicle utilisation.
VI. Examine safety-related indicators, including incidents, injury rates and claims.
VII. Develop an interactive dashboard that presents operational performance in an accessible format.
VIII. Identify opportunities for improving cost control, fleet efficiency, service reliability and safety management.
# Tools Used
Microsoft Excel: Data inspection, quality checks, preliminary analysis, supporting calculations, KPI presentation and filtering.
Power BI: Data modelling, KPI calculations, measure and column insertion using DAX, and interactive dashboards.
# Methodology [Data Analysis Approach]
The project follows a descriptive and diagnostic analytics approach.
Step 1. Data structure and preparation
The project data is structured around logistics entities and operational activities, including drivers, trucks, trailers, customers, facilities, routes, loads, trips, fuel purchases, maintenance records, delivery events and safety incidents.

Step 2: Data preparation and analysis
The relevant data is prepared and organised for analysis. Where applicable, this includes checking data quality, aligning related records and preparing measures for financial, operational and safety indicators.

Step 3: KPI development
Performance indicators are presented across the following areas:
Revenue and profit
Maintenance expenditure
On-time service performance
Lane and customer revenue
Driver performance and fuel efficiency
Fleet health and utilisation
Safety incidents, injury rates and claims

Step 4: Dashboard development
An interactive Power BI dashboard was developed to present key performance indicators, charts and tables. Booking-type and customer-type filters support more focused exploration, while navigation tabs separate the analysis into functional areas.

Step 5: Interpretation and recommendations
The dashboard outputs were reviewed to identify observable performance patterns and areas requiring management attention. Recommendations are presented as potential actions to investigate rather than as proven improvements.

# Key Findings
The following findings are based on the values and visualisations displayed in the supplied dashboard.

5.1 Revenue and profitability
Total revenue: 298.62M.
Total profit: 197.30M.
Total maintenance cost: 5.73M.
Overall on-time rate: 55.7%.
The dashboard indicates substantial reported revenue and profit alongside measurable maintenance expenditure. However, the meaning of the profit measure, the currency, and the treatment of operating costs should be documented before drawing conclusions about the overall financial health of the business.

5.2 Revenue trends
The yearly revenue chart shows approximately:
2022: 99.9M
2023: 98.9M
2024: 99.8M
Revenue appears broadly stable across these three years, with a small decrease in 2023 followed by a recovery in 2024. The displayed figures do not, by themselves, establish the causes of these changes.

5.3 Lane and customer performance
The lane analysis highlights differences in revenue across transport routes, while the customer analysis identifies the highest-revenue customers.
The dashboard displays top-lane revenue values of approximately 10.9M–11.2M and identifies First Group as the leading customer by revenue at approximately 10.4M. These results suggest that revenue is not distributed equally across all lanes and customers.
The lowest-performing lanes are also displayed, creating an opportunity to investigate route economics, service performance and the operational factors associated with weaker results. Low revenue alone does not necessarily mean a lane is unprofitable.

5.4 Service performance
The overall on-time rate is displayed as 55.7%. The annual pickup and delivery chart shows two service-performance series at approximately 66.7% and 44.6% across the displayed years.
These indicators suggest that service reliability warrants further examination. The difference between the two series also makes it important to assess pickup and delivery performance separately rather than relying exclusively on an overall service KPI.

5.5 Driver performance and fuel efficiency
The driver-performance dashboard reports:
Active drivers: 124
Average idle time: 7.01 hours
A displayed aggregate average-MPG measure of 29.02K
The dashboard also visualises fuel-efficiency distribution across drivers. This can support comparisons and help identify drivers or records requiring further investigation.
The 29.02K figure should be reviewed before being interpreted as an operational fuel-efficiency result, because summing average-MPG values may not provide a meaningful fleet-wide efficiency measure. A properly defined weighted or distance-based MPG metric would be more suitable for an overall assessment.

5.6 Fleet maintenance and safety
The fleet health dashboard displays:
Active trucks: 92
Total maintenance cost: 5.73M
Injury rate: 0.19
Total claims: 2.65M
The maintenance-cost chart shows several cost categories with displayed values of approximately 0.88M–0.96M for the leading categories. The annual incidents chart also indicates recorded incidents across the years shown.
These indicators provide a basis for monitoring maintenance expenditure and safety performance. However, the dashboard does not establish the causes of maintenance costs or incidents, nor does it show whether the injury rate is a percentage, a frequency rate or another measure.

# Recommendations
Based on the patterns displayed, the following actions are recommended for further investigation.
6.1 Improve service reliability
Investigate the factors contributing to the 55.7% overall on-time rate. Separate pickup and delivery performance, and examine delays by lane, customer, driver and time period to identify recurring operational bottlenecks.

6.2 Review lane-level performance
Assess the lowest-revenue lanes using revenue, direct operating costs, fuel expenditure, distance travelled and load utilisation. Consider route redesign, scheduling changes or service adjustments only after establishing each lane's profitability and strategic importance.

6.3 Strengthen customer performance monitoring
Review revenue concentration among leading customers and compare it with service requirements, operating costs and customer retention. This would provide a more balanced view of customer value than revenue ranking alone.

6.4 Optimise fuel efficiency and driver utilisation
Investigate high idle time and variation in driver fuel-efficiency records. Review driving behaviour, vehicle condition, route characteristics and idle-time causes. Use clearly defined and comparable fuel-efficiency measures before setting targets.

6.5 Adopt preventive maintenance monitoring
Examine the largest maintenance-cost categories, recurring repairs and vehicle downtime. Use maintenance history and vehicle utilisation data to identify opportunities for preventive maintenance and reduce avoidable service disruption.

6.6 Strengthen safety management
Investigate the nature, location and frequency of incidents, alongside injury and claims records. Use exposure-adjusted safety measures where appropriate and prioritise interventions based on validated incident patterns.

6.7 Improve KPI definitions and reporting
Document the formulas, units, reporting periods and data sources for every KPI. In particular, validate the profit calculation, the on-time-rate definition, the injury-rate unit and the aggregate MPG measure. This will improve comparability and support more reliable management decisions.

# Project Files
README.md - showing the project overview, objectives, methodology, findings and limitations.
Excel - Selected workbooks containing supporting analysis
PowerBI - The power BI project file.
Images - Screenshots of dashboards and charts.

# Limitations

The findings should be interpreted in light of the following limitations:

I. Dashboard-level evidence: The supplied dashboard provides summary figures and visual patterns, but it does not independently establish the causes of observed performance.

II. KPI definitions: Some measures require clarification, including the currency, profit calculation, injury-rate unit and the method used to calculate the aggregate MPG figure.

III. Profitability detail: Revenue rankings alone cannot establish route or customer profitability without the associated operating costs.

IV. Causal interpretation: The displayed relationships and trends do not establish that any particular driver, route, vehicle or customer caused a performance outcome.

# Author's Contribution

I developed and presented this logistics operations analytics project as a portfolio demonstration of data visualisation and operational performance analysis. The dashboard organises logistics KPIs into financial performance, lanes and customers, driver performance, and fleet health and safety, enabling users to explore multiple aspects of the operation through a single interactive reporting interface.

My demonstrated contribution includes the data cleaning, DAX measure creation, presentation of key performance indicators, the organisation of visualisations into functional dashboard sections, and the interpretation of displayed metrics to identify areas for further investigation.


# Conclusion

This project demonstrates how an interactive dashboard can consolidate financial, service, driver, fleet and safety indicators into a single view of logistics operations. The results highlight opportunities to investigate service reliability, lane-level economics, fuel efficiency, maintenance expenditure and safety performance.

The dashboard provides a foundation for further analysis. Validated KPI definitions, detailed operating-cost data and documented data-preparation steps would enable deeper investigation and more reproducible conclusions.

**_Author: Victor Komolafe_**

Project area: Data Analytics | Logistics and Supply Chain Management | Operational Performance

**Dashboard tool: Microsoft Power BI**


