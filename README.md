Data Cleaning and Preprocessing – Medical Appointment Dataset
This repository demonstrates data cleaning and preprocessing of a medical appointment dataset using Python (Pandas).
The goal is to prepare raw data for analysis and machine learning by handling missing values, fixing data types, and standardizing formats.

Dataset Overview
Rows: 110,527

Columns: 14 (Patient info, appointment details, medical conditions)

Key Columns:

PatientId, AppointmentID

Gender, Age, Neighbourhood

ScheduledDay, AppointmentDay

No-show (Target column)

Cleaning & Preprocessing Steps
Removed duplicate rows.

Standardized column names (lowercase, underscores).

Converted date columns to datetime format.

Standardized Gender values: M → Male, F → Female.

Fixed data types for PatientId and Age.

Exported cleaned dataset for further analysis.

Deliverables
Jupyter Notebook: data cleaning and preprocessing.ipynb

Cleaned CSV: Day-1_cleaned.csv


