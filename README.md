# Patient Wait List Analysis Dashboard

<h2><a href="https://app.powerbi.com/view?r=eyJrIjoiZjc2MzQ4YTUtMGViMS00MDExLTgxYzgtZjc5MmNhOGE4MTRlIiwidCI6IjQ4OGZjOWE4LTU0ZDEtNGJjYS1hYmRiLTUzNmIyNTMxM2ZmZiJ9" target="_blank">PowerBI Dashboard Link</a></h2>

## Project Overview

This Power BI project visualizes patient wait list data, enabling detailed analysis of various case types, specialties, and age profiles. The dashboard provides real-time insights into patient statistics for a specified date range, empowering decision-makers to monitor healthcare capacity, spot trends, and improve operational efficiency.

## Key Features

- **Date Range Filtering**: Easily adjust the archive date range to explore historical trends.
- **Case Type Segmentation**: Compare patient wait lists by **Day Case**, **Inpatient**, and **Outpatient** categories.
- **Specialty and Age Profiles**: Analyze patient distribution across specialties like Accident & Emergency and Anaesthetics, broken down by age profiles (0-15, 16-64, 65+).
- **Time Bands Visualization**: A dynamic representation of time spent in the system for different patient age groups, helping to uncover bottlenecks and highlight areas needing improvement.
- **Performance Metrics**: Key performance indicators (KPIs) display the total wait list counts for both the current and previous year, allowing easy comparison of healthcare performance over time.
- **Data Model Optimization**: Designed a data model with fact and dimension tables to streamline query performance and enhance reporting efficiency in Power BI.


## Visual Breakdown

1. **Summary View**:
   - **KPI Comparison**: Displays the total wait list count for the current and previous year.
   - **Pie Chart Distribution**: Shows the percentage breakdown of **Outpatient**, **Day Case**, and **Inpatient** patients.
   - **Time Band vs Age Profile**: A stacked bar chart illustrating how long patients of different age groups are waiting.
   - **Monthly Trends**: Line charts display patient trends over time, segmented by **Case Type** (Day Case, Inpatient, and Outpatient).

   ![Summary View](https://github.com/laxmikantmkabra/HealthCare-Power-BI-Dashboard/assets/143458925/b19e402c-9e25-44ab-bf13-ecf998bf8a24)


2. **Detailed View**:
   - Users can filter and drill down by date, case type, specialty, and age profile.
   - Total patient counts by case type are displayed, with breakdowns by months waited.
   
   ![Detailed View](https://github.com/laxmikantmkabra/HealthCare-Power-BI-Dashboard/assets/143458925/c8b45594-03f4-4322-868a-0606c7194b7f)


## Technology Used

- **Power BI**: For data visualization and dashboard development.
- **Power Query Editor**: Data was initially cleansed, processed and transformed after importing into Power BI.
- **Excel**: Data was present into csv format and minimal pre-processing was performed

## Insights

This dashboard provides a comprehensive view of patient wait lists across multiple categories. It enables healthcare administrators to:
- Track fluctuations in patient volumes over time.
- Identify which specialties are under the most pressure.
- Gain insights into how different age groups are affected by wait times.

## Conclusion

The **Patient Wait List Analysis Dashboard** offers a robust tool for healthcare professionals to monitor patient flow, identify inefficiencies, and make data-driven decisions to improve healthcare services.
