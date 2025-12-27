📊 City Safety & Incident Analytics Dashboard
🔎 Project Overview
This project demonstrates an end-to-end Business Intelligence workflow using SQL, Power Query, DAX, and Power BI.
The goal is to analyze urban safety incidents (simulated CCTV logs + demographic data) and provide actionable insights for city management.

🎯 Business Problem
City authorities often struggle to understand:
- Which areas have the highest incident rates
- How response times vary by district
- What types of incidents are increasing over time
This dashboard answers these questions with interactive visualizations and data-driven KPIs.

🛠️ Workflow
- Data Source
- Raw CSV files: incident logs, population data
- SQL database for structured queries
- ETL Process
- Cleaned timestamps, standardized categories
- SQL scripts for preprocessing
- Power Query for transformations
- Data Model
- Relationships between incidents, locations, and demographics
- DAX measures: YOY growth, rolling averages, response time KPIs
- Visualization
- Incident trends over time
- Heatmap by district
- Response time distribution
- Drill-down by incident type
- We can do:
 - Calculate response times (Closed Date - Created Date).
 - Group by borough for per capita analysis.
 - Categorize complaint types (Noise, Parking, Sanitation, Heating, etc.).
 - Visualize open vs closed requests.


📈 Dashboard Features
- KPIs: Total incidents, average response time, YOY growth
- Interactive Filters: District, incident type, time period
- Forecasting: Predict incident trends for next 6 months
- Role-Level Security (RLS): District-level access control

📂 Repository Structure

📂 PowerBI-CitySafety

 ┣ 📁 Data
 ┃ ┗ incidents_raw.csv
 
 ┣ 📁 SQL
 ┃ ┗ transformations.sql
 
 ┣ 📁 PowerBI
 ┃ ┗ CitySafety.pbix
 
 ┣ 📁 Documentation
 
 ┃ ┗ README.md
 
 ┗ 📁 Images
    ┗ dashboard_preview.png



📸 Dashboard Preview
(Insert screenshot here)

🔑 Key Insights
- District A has the highest incident density per capita
- Response times improved by 12% YOY after policy changes
- Theft incidents show a seasonal spike in summer months

🚀 How to Reproduce
- Clone this repository
- Import incidents_raw.csv into SQL or Power BI
- Run transformations.sql for preprocessing
- Open CitySafety.pbix in Power BI Desktop
- Explore the dashboard

📌 Future Enhancements
- Add real-time streaming data from IoT sensors
- Integrate predictive analytics with Python/R
- Expand to include traffic and environmental data

👉 This README positions you as someone who can design, clean, model, and visualize data professionally.
Would you like me to also draft a second README.md template for a business-focused project (like Retail Sales Dashboard) so you can show variety in your portfolio?
