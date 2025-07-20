🎓 **NLCPHS Student Performance Dashboard**

📌 **Overview**

The NLCPHS Student Performance Dashboard is a comprehensive, automated data visualization solution built to track and analyze key student performance indicators. The project integrates data engineering (Python, SQL, GCP), ETL, and advanced Tableau dashboarding to deliver real-time, actionable insights for educators and administrators at NLCPHS.

⚙️ **Key Features**

🔄 Automated Data Pipeline: Python scripts fetch data from the PowerSchool API, clean and transform it, and load it into a MySQL database—all scheduled on a GCP-hosted virtual machine.

🧹 Data Cleaning & Transformation: Removed redundant columns, handled null values, fixed data types, and de-duplicated entries before storing them in GCP MySQL.
🧩 Optimized SQL Views: Created school-specific SQL tables and views to structure data for dashboard use and ensure performance efficiency.
📊 16 Dynamic Tableau Dashboards: Designed to monitor:

**Student attendance**

**GPA trends and academic grades**

**Behavior logs and incident reports**

**Growth targets and benchmark performance**

🎛️ **Dynamic Parameters & Filtering:** Users can interact with the dashboards using dropdowns and filters that update all related visuals simultaneously.

🔢 **Custom Calculated Fields:** Built complex logic in Tableau to derive KPIs, flags, growth metrics, and benchmark-level interpretations.

🚀 **End-to-End Automation:** Ensures real-time dashboard refreshes with minimal manual intervention.



📁 **Repository Structure**

**NLCPHS_Student_Performance_Dashboard/**

Dashboard Documentation/ – Contains Word documents explaining dashboard logic and insights.

Data Pipeline/ – Contains Word documentation of the Python → MySQL → GCP data flow.

Dashboards with their respective data sources.xlsx – Excel file mapping each Tableau dashboard to its dataset.

Python Scripts/ – Contains .py files for API extraction, data cleaning, and transformation.

Tableau Dashboard files/ – Contains Tableau .twb or .twbx files for the dashboards.

README.md – Project overview, features, structure, and usage instructions.

🛠️**Tech Stack**

Python (API access, ETL automation)

Google Cloud Platform (VM, MySQL instance)

SQL (MySQL) (Schema design, custom views)

Tableau (Dashboards, calculated fields, dynamic parameters)

PowerSchool API (Primary data source)

🎯**Use Case**

This solution is ideal for school districts or institutions looking to:

Monitor real-time student performance

Automate data flows from SIS systems (e.g., PowerSchool)

Reduce manual reporting overhead

Improve decision-making with intuitive visuals


🧠 **Insights Delivered**

Identification of at-risk students through combined GPA + behavior trend metrics.

Improved transparency for teachers and school leaders through interactive drill-downs.

Visual alerts for students not meeting academic or behavioral benchmarks.

Grade-level and subgroup-specific performance tracking for equity analysis.
