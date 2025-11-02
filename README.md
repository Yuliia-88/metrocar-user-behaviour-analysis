# 🚗 Metrocar User Behaviour Analysis

## 📌 Project Overview  
This project analyzes user behavior on the Metrocar platform to uncover patterns and improve user experience. It focuses on:
- Conversion funnel analysis  
- User interaction tracking  
- Age-based segmentation

## 🗂️ Data Sources
- PostgreSQL database - the primary source containing raw user and trip data, accessed via structured SQL queries
- Exported query results (CSV format) - selected datasets were exported as CSV files for further analysis in Google Sheets and Power BI
- data/ folder - contains all exported CSV files used in this project, including user profiles, trip logs, event data, and calculated metrics such as waiting times

## Database shema

![](database_shema.png)

## 🧰 Tools Used
- **Docker** - for locally deploying the metrocar database in a containerized environment.
- **DBeaver** - for visualizing the database structure, testing SQL queries, browsing data, and exporting results to CSV for further analysis
- **SQL (PostgreSQL)** - for querying, aggregating and preprocessing the data
- **Google Sheets** - for initial analysis, pivot tables, and building PDF and CDF functions of waiting time
- **Power BI** - for interactive dashboards and visual data storytelling

## 📈 Visualizations  
Power BI Dashboards include:
- User and trip funnels - visualizing drop-off points across the registration and ride completion process
- User distribution by platform type - comparing engagement across mobile and web platforms
- Hourly breakdown of completed and cancelled rides - identifying peak times and cancellation patterns

[To go to this interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjQ4MTUzNmUtNWM0Zi00Nzc0LWIzMTEtODQwMGZhYWJlOGI4IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

![](dashboard_metrocar.png)

Google Sheets analysis include:
- [PDF and CDF functions of waiting time](https://docs.google.com/spreadsheets/d/1yQ5enABx7nCfaYtZgPFU126j8SZRcWcR3A4grMDZcns/edit?usp=sharing)
- [Analyzing user behavior between ride request confirmation and cancellation](https://docs.google.com/spreadsheets/d/1ZlSuZlLCLMSRTIdb-LmIihEyuSwh08x9MyQWGBJe4PU/edit?usp=sharing)

SQL queries:
[View SQL queries in Notion](https://www.notion.so/MidTerm-Project-Metrocar-Data-Analysis-205cda259e6580949757cabe26150b78?source=copy_link)

## 📊 Key Insights  
- Identified drop-off points in the user funnel  
- Mapped behavioral trends across different age groups  
- Highlighted platform features with low engagement

## 🖋️ Author

👩‍💻 Yuliia Klymenko

Data Analyst | SQL | Python | Excel & Google Sheets | Power BI | Tableau
