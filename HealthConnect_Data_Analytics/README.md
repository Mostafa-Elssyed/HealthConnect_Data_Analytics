# 📊 HealthConnect Clinic - Data Analytics Portfolio

## 📌 Project Problem Statement
HealthConnect Clinic is facing significant operational inefficiencies driven by high patient appointment no-show frequencies and administrative overhead from repetitive inquiries. This project leverages data analytics pipelines to isolate the behavioral, spatial, logistical, and temporal variables causing patient defaults.

## 📂 Experience Lab Directory Structure
* **`data/`** — Houses raw resources (`HealthConnect_Appointment_Data.csv` and the Data Dictionary mapping matrix).
* **`src/`** — Stores data profiling scripts (`verify_data.py`).
* **`documentation/`** — Contains official milestone reports (`Initial_Analysis_Document.txt` and `Week_4_Project_Summary.txt`).
* **`README.md`** — Portfolio profile front page.

## 📅 Week 4 Foundations Established
* **Environment Configuration:** Successfully integrated a local VS Code instance with an Anaconda base Python execution interpreter environment.
* **Data Quality Profiling:** Executed automated script checks verifying 5,000 distinct row vectors across 18 unique operational parameters.
* **Missingness Scanned:** Programmatically isolated structural gaps across `reminder_channel` (1,366 lines), `distance_to_clinic_km` (90 values), and `waiting_time_minutes` (60 values).
* **KPI Matrix Engineered:** Formulated 5 target metric schemas (RSD, AIWD, LTAI, DVNR, RACR) to map attendance trends against scheduling and physical access barriers.

## 🚀 Next Horizon: Week 5
Moving into the development stage to write data cleaning functions, handle missing entries via grouped median imputation, and deploy exploratory visualization layouts inside Power BI.