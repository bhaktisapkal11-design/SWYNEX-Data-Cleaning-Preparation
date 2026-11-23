# Swynex Task 1 — Healthcare Data Cleaning & Preparation

## Dataset
- Raw File: `swynex_healthcare_hospital_raw.csv`
- Cleaned File:** `swynex_healthcare_hospital_cleaned.csv`

## Changes Made
- Missing Values:Handled blank/placeholder entries (`N/A`, `Unknown`, `None`, `null`) and filled missing `age`, `satisfaction_score`, `billing_amount`, `insurance_provider`, and `discharge_outcome` values.

- Duplicates:Removed duplicate rows and duplicate `patient_id` records.

- Data Types:Cleaned currency text (`₹`, `INR`, commas) in `billing_amount` to numeric values, converted `age` and `satisfaction_score` to integers, and parsed dates into `YYYY-MM-DD`.

- Inconsistent Values:** Standardized `patient_name`, `gender`, and `medical_condition` formatting, fixed swapped admission/discharge dates, and added `length_of_stay_days`.
