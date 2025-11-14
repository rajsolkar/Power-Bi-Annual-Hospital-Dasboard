🏥 Annual Hospital Analysis Dashboard
📌 Project Overview

This Power BI dashboard provides a comprehensive analysis of key performance indicators (KPIs) and operational metrics for a hospital’s yearly performance. It helps management, finance teams, and clinical staff monitor:

Financial health

Patient activity

Appointment outcomes

Treatment & doctor performance

The dashboard is built using data from January 1, 2023, to December 30, 2023.

⭐ Key Features & Metrics
1. Financial Performance

Total Revenue: $99K

Outstanding Revenue: $67K

Average Bill Amount: $2.76K

Highest Treatment Cost: $4.85K

📸 Screenshot to add:
➡️ Add a screenshot of your Revenue KPI section
Place filename: screenshots/financial_kpi.png

2. Patient & Appointment Activity

Total Active Patients: 12

Total Appointments: 16

Completion Rate: 25%

No-show Rate: 25%

📸 Screenshot to add:
➡️ Add a screenshot of Patients + Appointment KPIs
Place filename: screenshots/patient_kpis.png

3. Core Visualizations
A. Appointments Over Time (Area Chart)

Shows how appointment volume changes month-to-month.

📸 Screenshot: screenshots/appointments_over_time.png

B. Revenue by Payment Method & Status (Stacked Bar Chart)

Breakdown of Cash, Insurance, and Credit Card payments categorized by Paid, Pending, and Failed.

📸 Screenshot: screenshots/payment_method_status.png

C. Appointment Status Distribution (Donut Chart)

Visual distribution of Completed, Scheduled, Cancelled, and No-Show appointments.

📸 Screenshot: screenshots/status_distribution.png

D. Top Doctor Analysis

Showcases the doctor with the highest number of completed appointments (e.g., Linda Brown – 4 Completed Appointments)

📸 Screenshot: screenshots/top_doctor.png

4. Interactive Slicers

Users can interact with the report using:

Timeline slicer (filter date range)

Doctor slicer

Treatment Type slicer (MRI, X-Ray, Physiotherapy, ECG, etc.)

📸 Screenshot: screenshots/slicers.png

🛠 Technical Requirements

You need the following to view the dashboard:

Power BI Desktop (Free)

Power BI Pro/Premium only if you want to publish and share online

🚀 Setup Instructions
1. Clone the Repository
git clone https://github.com/your-username/your-repo-name.git

2. Open the Dashboard

Open the Power BI file:

hospital.pbix

3. (If needed) Update File Paths

If prompted:

Go to
File → Options & Settings → Data Source Settings
and update the data source paths.

🧱 Data Model

This project uses a Star Schema:

Fact Table

Fact_Appointments

Dimension Tables

Dim_Doctor

Dim_Patient

Dim_Treatment

Dim_Date

📸 Screenshot: screenshots/model_view.png

Data Source (Example):
https://www.kaggle.com/datasets/kanakbaghel/hospital-management-dataset

📬 Contact

Raj Solkar
Aspiring Data Analyst | AI Enthusiast

📧 Email: rajsolkar26@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/raj-solkar-26032006m/

🐙 GitHub: https://github.com/rajsolkar
