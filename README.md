# 🏥 Healthcare Data Analytics Project

**Duration:** 27th June 2025 – 4th July 2025  
**Tools Used:** Excel | DAX | Power query | Power BI

## 📌 Project Overview
In the modern healthcare system, delivering timely and efficient care is more important than ever. One of the biggest operational challenges hospitals face is managing patient wait times — especially in outpatient departments where appointment volume is high and resources are limited. This project focuses on using data analytics to uncover patterns in patient appointment behavior, doctor availability, and departmental performance. By analyzing hospital appointment records from January to February 2025, we aim to find out:
- Why patients are waiting longer than expected,
- Which departments or doctors face delays,
- What time slots or days are most affected.

The ultimate goal is to convert raw hospital data into actionable insights that can help healthcare administrators optimize appointment scheduling, reduce bottlenecks, and improve both patient experience and staff productivity. To communicate these findings clearly, we developed an interactive Power BI dashboard that visualizes appointment trends, peak wait times, and doctor/department performance. This case study not only addresses a real healthcare problem but also demonstrates how data tools like Excel, SQL, and Power BI can solve complex operational issues.

## 📌 Problem statement
Long patient wait times are a common issue across healthcare systems. They affect not just **patient satisfaction**, but also the hospital’s **revenue, staff morale, and operational efficiency**.
These delays are often caused by:
- Poor scheduling systems,
- Uneven doctor workloads,
- Lack of data-driven insights into appointment trends.

Even though hospitals generate large amounts of operational data, they often **don’t analyze it effectively**. This leads to missed opportunities for optimization.
In this project, we aim to:
- Identify the causes of long wait times,
- Highlight overloaded doctors and departments,
- Analyze daily and hourly appointment trends,
- Propose practical and data-backed improvements.

## 🎯 Objectives

- Analyze average and peak patient wait times
- Identify overloaded departments or doctors
- Discover time-of-day or day-of-week wait patterns
- Propose scheduling and resource allocation improvements
- Build an interactive Power BI dashboard
- Create a portfolio-ready healthcare case study

---

## 🧩 Dataset Details

The dataset includes 7 columns:
- `Patient_ID`
- `Patient_name`
- `Appointment_date`
- `Arrival_time`
- `Consultation_start_time`
- `Department` (e.g., Neurology, Cardiology)
- `Doctor_ID`

📅 **Date Range:** January 2025 – February 2025  
🧑‍⚕️ **Departments Covered:** Neurology, Cardiology, Dermatology, Orthopedics, Pediatrics  
👨‍⚕️ **Doctors:** 10 unique IDs (DR100–DR109)

---

## 🛠️ Project Workflow

### 1. Data Understanding & Problem Statement
- Analyzed the key challenges hospitals face with patient wait time.
- Defined the scope: department/doctor-wise delays and scheduling inefficiencies.

### 2. Data Cleaning & Transformation
- Removed nulls and duplicates
- Converted time columns to datetime format
- Calculated `Wait Time = Consultation_start_time - Arrival_time`

### 3. Descriptive Analysis (Excel / Power Query)
- Department-wise & doctor-wise average wait times
- Appointment trends (daily, weekly, monthly)
- Peak hours of delays
- Patients waiting over expected thresholds

### 4. Dashboard Development (Power BI)
- Page 1: Overview – total appointments, weekday load, avg wait time
- Page 2: Department & doctor-wise comparison
- Page 3: Time-based trends (hourly/daily/monthly)

### 5. Insights Generated
- Neurology & DR102 had the highest average wait times
- Peak wait times: 1 PM, 3 PM, and midweek days
- Wait time is nearly the same on weekdays & weekends, showing staffing imbalance

### 6. Solutions Proposed
- Redistribute doctor load (especially DR102)
- Auto-suggest off-peak slots for patients
- AI-powered scheduling to optimize slot lengths
- Real-time queue visibility for admin staff
- Promote weekend appointments with offers

### 7. Project Limitations
- Only 2 months of data (no seasonal trends)
- No data on no-shows or consultation duration
- No patient feedback or demographics

---

## 📊 Deliverables

| File/Asset | Description |
|------------|-------------|
| `Healthcare_Data.csv` | Cleaned & transformed dataset |
| `PowerBI_Dashboard.pbix` | Interactive dashboard |
| `Healthcare Data Analytics Project.pdf` | Full project report |
| `README.md` | Project documentation |

---

## 🔍 Sample Questions Answered

- What is the average wait time?
- Which doctor/department has the longest delays?
- What time/day sees the most delays?
- Do more appointments always mean higher wait time?

---
