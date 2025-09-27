# 🏥 Patients Dashboard (Power BI)

## 📌 Project Overview
This project presents an **interactive Power BI dashboard** built using simulated hospital ER data (not actual patient records).  
The aim is to analyze **patient visits, wait times, satisfaction levels, and referrals** to support hospital management with data-driven decisions.  

---

## ⚙️ Steps of the Project

### 1️⃣ Data Cleaning and Transformation
- Imported the dataset (`Hospital ER.csv`) into Power BI.  
- Checked data quality: no duplicates, no errors, no significant outliers.  
- Handled missing values.  
- Standardized column data types.  
- Created a **Full Name** column by merging first initial + last name.  
- Added a **Moment (AM/PM)** column based on visit time.  

### 2️⃣ Data Modeling
- Built a **Date Table** with calculated columns (Year, Month, Weekday, etc.).  
- Marked the Date Table as the official date table.  
- Connected `Date[Date]` with `Patients Dataset[date]`.  
- Since the dataset contains only one main table, no additional relationships were required.  

### 3️⃣ Measures (DAX Calculations)
- Created measures for KPIs such as Total Patients, Avg. Satisfaction, Avg. Wait Time.  
- Built percentage-based measures for referrals, administrative appointments, gender distribution, and service ratings.  
- Added measures to highlight **max/min patient visits** by month and year.  
- A full list of measures is documented in **Important_Measures.txt**.  

### 4️⃣ Dashboard Design
The final dashboard includes:  

- **KPIs**  
  - Total Patients  
  - % Administrative Appointment  
  - % None Administrative Appointment  
  - Average Satisfaction Score  
  - % Service Not Rated  
  - Average Wait Time  
  - % Referred Patients  
  - % Walk-in Patients  
  - % Female Visits  
  - % Male Visits  
  - % Unknown Visits  

- **Slicer**  
  - Time of visit (AM / PM)  

- **Visuals**  
  - Line chart: Total Patients Visits by Month (with max/min highlights).  
  - Line chart: Total Patients Visits by Year (with max/min highlights).  
  - Pie chart: Total Patients Visits by Weekday Type.  
  - Bar chart: Total Patients by Department Referral.  
  - Bar chart: Total Patients by Age Group.  
  - Matrix: Patient Race × Age Buckets, with parameter to switch between Avg. Satisfaction and Avg. Wait Time.  

---

## 🚀 Value for Clients
This dashboard helps hospital management to:  
- Track performance through **clear KPIs** (patients, satisfaction, wait times, referrals, demographics).  
- Identify **trends and peak periods** to improve staff allocation and planning.  
- Compare **referrals vs walk-ins** to optimize service flow.  
- Analyze **patient satisfaction and wait times** to improve quality of care.  
- Gain insights into **demographics** (age, gender, race) for better service delivery.  

These insights empower hospital leaders to make smarter, data-driven decisions that enhance efficiency and improve patient care.  

---

## 📂 Repository Structure
- **Icons/** → Custom icons used in the dashboard.  
- **Images/** → Screenshots of the dashboard and the data model.  
- **Hospital ER.csv** → Dataset used in the project.  
- **Patients Dashboard.pbix** → Power BI file with full project.  
- **Important_Columns.txt** → dataset created columns.
- **Important_Measures.txt** → List of created measures.
- **Important_Tables.txt** → created tables structures.

---

## 📬 Contact
👩‍💻 Engy Saeed  
📧 Email: engysead498@gmail.com
🔗 [LinkedIn Profile](https://www.linkedin.com/in/engy-saeed-b47784276/)
