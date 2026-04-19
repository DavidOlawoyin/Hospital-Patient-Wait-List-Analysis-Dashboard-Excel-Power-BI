
🏥 Hospital Patient Wait List Analysis | Excel | Power BI Dashboard

📊 End-to-end healthcare analytics project analysing inpatient, day case, and outpatient wait lists to identify trends, specialty pressure, and long-wait bottlenecks.
________________________________________

📌 Table of Contents

•	🚨 Problem Statement

•	🎯 Project Objectives

•	📂 Dataset Overview
•	🧹 Data Preparation
•	🏗️ Data Model
•	📊 Dashboard Overview
•	📌 Key Metrics
•	🔍 Key Insights
•	🎯 Business Impact
•	🛠️ Tools & Technologies
•	📸 Dashboard Preview
•	🚀 Future Improvements
•	📝 Conclusion
________________________________________
🚨 Problem Statement
Healthcare systems face increasing pressure to manage growing patient demand while ensuring timely access to care. Patient wait list data is often fragmented across multiple files and systems, making it difficult to monitor trends, identify bottlenecks, and prioritise high-demand specialties.
Without a unified analytical view, healthcare teams struggle to track long waiting times, compare inpatient and outpatient performance, and make informed operational decisions. This can result in prolonged waiting periods, inefficient resource allocation, and reduced patient satisfaction.
This project addresses these challenges by consolidating multi-year wait list data into a single Power BI dashboard, enabling clear visibility of trends, wait time distributions, and specialty-level demand to support data-driven decision-making.
________________________________________
🎯 Project Objectives
•	Analyse wait list trends across multiple years (2018–2021)
•	Compare inpatient, day case, and outpatient pathways
•	Identify specialties with highest demand and delays
•	Break down patients by waiting time bands (0–3 months to 18+ months)
•	Provide a clear and interactive reporting solution for stakeholders
________________________________________
📂 Dataset Overview
📁 Data Sources
•	Inpatient Wait List (2018–2021)
•	Outpatient Wait List (2018–2021)
•	Specialty Mapping Table
📊 Key Fields
•	Archive_Date – Monthly reporting date
•	Case_Type – Inpatient / Day Case / Outpatient
•	Specialty_Name – Clinical specialty
•	Age_Profile – Patient age grouping
•	Time_Bands – Waiting time categories
•	Total – Number of patients
________________________________________
🧹 Data Preparation
•	Combined multiple yearly CSV files into unified datasets
•	Standardised column names across inpatient and outpatient data
•	Cleaned inconsistent labels (specialties, time bands)
•	Removed null and unnecessary columns
•	Joined specialty mapping for grouped analysis
•	Prepared date field for time-based trend analysis
________________________________________
🏗️ Data Model
•	Built a structured data model in Power BI
•	Created relationships between wait list data and specialty mapping
•	Designed slicers for:
o	Time Bands
o	Case Type
o	Specialty
o	Age Profile
________________________________________
📊 Dashboard Overview
🔹 Summary Page
•	Latest Month Wait List
•	Previous Year Comparison
•	Total Inpatient & Outpatient
•	Wait list distribution by case type
•	Top 5 specialties by wait list
•	Monthly trend analysis
🔹 Inpatient & Day Case Details
•	Monthly breakdown by time bands
•	Detailed patient counts
•	Interactive filtering
🔹 Outpatient Details
•	Long wait categories (18+ months)
•	Specialty-level analysis
•	Trend monitoring
________________________________________
📌 Key Metrics
•	📍 Latest Month Wait List
•	📍 Previous Year Latest Month Comparison
•	📍 Total Inpatient
•	📍 Total Outpatient
•	📍 Average Wait List by Case Type
•	📍 Wait List by Time Bands
•	📍 Top Specialties by Demand
________________________________________
🔍 Key Insights
•	Outpatient services account for the largest share of wait list volume
•	Latest wait list levels exceed previous year levels, indicating increasing demand
•	Certain specialties consistently show higher patient backlogs
•	Long waiting time categories (12+ months, 18+ months) highlight service pressure areas
•	Trend analysis reveals periods of growth and potential system strain
________________________________________
🎯 Business Impact
•	Enables better visibility of healthcare demand
•	Supports early identification of service bottlenecks
•	Helps prioritise high-demand specialties
•	Improves decision-making for resource allocation
•	Enhances monitoring of long-wait patients
________________________________________
🛠️ Tools & Technologies
•	Power BI – Dashboard design and data visualization
•	CSV Data Sources – Raw healthcare data
•	Data Modelling – Relationships and filtering logic
•	Excel / Data Cleaning – Pre-processing and validation
________________________________________
📸 Dashboard Preview
📊 Summary View
<img width="1175" height="755" alt="image" src="https://github.com/user-attachments/assets/057bf88e-100f-4462-90dd-718127c1a349" />

📊 Inpatient & Day Case Details
<img width="1125" height="753" alt="image" src="https://github.com/user-attachments/assets/3be1dc90-a690-42a9-8020-da93ad473d98" />

 📊 Outpatient Details
 <img width="1152" height="756" alt="image" src="https://github.com/user-attachments/assets/6bce0b14-7f97-48ee-8fda-c12104e48581" />
________________________________________
🚀 Future Improvements
•	Add year-over-year growth metrics
•	Include alert indicators for long wait thresholds
•	Build advanced time intelligence using DAX
•	Add drill-through pages for deeper analysis
•	Integrate real-time or automated data updates
________________________________________
📝 Conclusion
This project demonstrates how healthcare wait list data can be transformed into actionable insights using Power BI. By consolidating multiple datasets into a structured dashboard, it provides a clear view of patient demand, waiting time distribution, and specialty pressure areas.
The solution supports healthcare organisations in improving operational efficiency, reducing waiting times, and enhancing patient care delivery through data-driven decision-making.

