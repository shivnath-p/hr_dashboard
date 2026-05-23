📊 HR Analytics Dashboard

Transforming raw employee data into strategic workforce intelligence — built with Tableau
🧠 What This Project Does
This interactive Tableau dashboard gives HR teams and business leaders a 360° view of workforce health — from attrition hotspots to job satisfaction patterns — all in one place. No more digging through spreadsheets.

🔢 Key Metrics at a Glance
MetricValue👥 Total Employees1,470🚪 Employees Who Left237📉 Attrition Rate16.12%✅ Currently Active1,233🎂 Average Age37 years♂️ Male Attrition150♀️ Female Attrition87

📁 Dataset Overview
The dataset contains 1,470 employee records with 35+ features including:
CategoryFields🏢 Job InfoDepartment, Job Role, Job Level, Business Travel💰 CompensationDaily Rate, Hourly Rate, Monthly Income, Salary Hike %😊 SatisfactionJob Satisfaction (1–4), Environment Satisfaction, Work-Life Balance🎓 BackgroundEducation, Education Field, Years at Company, Training Times📊 PerformancePerformance Rating, Years Since Last Promotion, Stock Option Level

📌 Source: IBM HR Analytics Employee Attrition & Performance dataset


📈 Dashboard Breakdown
1. 🍕 Department-wise Attrition
Shows which departments are bleeding talent:

Sales → 56.12% of attrition (133 employees)
R&D → 38.82% (92 employees)
HR → 5.06% (12 employees)

2. 📊 Employees by Age Group
Histogram (bin size = 3) showing workforce age distribution — peak concentration in the 30–36 age band with 190–213 employees per bin.
3. ⭐ Job Satisfaction Rating (Heatmap)
Cross-tabulation of Job Role × Satisfaction Score (1–4):

Sales Executive leads with 326 total employees
Research Scientist shows high satisfaction scores at levels 3 & 4
Laboratory Technician has 259 employees — largest technical group

4. 🎓 Education Field-wise Attrition

Life Sciences: 89 exits (highest)
Medical: 63 exits
Marketing: 35 exits
Technical Degree: 32 exits

5. 🍩 Attrition Rate by Gender × Age Group
Donut charts reveal where attrition is most critical:
Age GroupTotal AttritionKey InsightUnder 25388.44% female, 29.11% male25–34112 ⚠️Highest risk cohort35–4451Stabilizing45–5425Low riskOver 5511Near-retirement, expected

🛠️ Tools & Tech
📌 Tableau Desktop    →  Dashboard design & interactivity
📌 Microsoft Excel    →  Data cleaning & preprocessing
📌 IBM HR Dataset     →  35 features × 1,470 records

🗂️ Repository Structure
hr-analytics-dashboard/
│
├── 📊 HR_Analytics_Dashboard.twbx   # Packaged Tableau workbook
├── 📄 HR_Employee_Data.xlsx          # Raw dataset (1,470 records)
├── 🖼️ dashboard_preview.png          # Dashboard screenshot
└── 📝 README.md                      # You're reading it!

