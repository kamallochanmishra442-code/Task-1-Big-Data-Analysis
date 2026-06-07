# 🏥 CODTECH IT Solutions — Data Analytics Internship
## Task 1: Big Data Analysis
### Project: Hospital Patient Records — Big Data Analysis using Dask

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Dask](https://img.shields.io/badge/Dask-Big%20Data-EF7C35?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Healthcare](https://img.shields.io/badge/Domain-Healthcare-brightgreen?style=for-the-badge)

</div>

---

## 📋 Internship Details

| Field | Details |
|-------|--------|
| **Name** | Kamal Lochan Mishra |
| **Intern ID** | CTIS05S1 |
| **Domain** | Data Analytics |
| **Duration** | 4 Weeks |
| **Mentor** | Neela Santhosh Kumar |
| **Company** | CODTECH IT Solutions Pvt. Ltd. |
| **Task** | Task 1 — Big Data Analysis |

---

## 🎯 Project Overview

> Perform **Big Data Analysis** on a large hospital patient dataset (**10,000 records × 31 columns**) using **Dask** for scalable parallel processing. Derive actionable healthcare insights on revenue, departments, patient demographics, admission trends, and treatment patterns.

---

## 🗂️ Project Structure

```
Task-1-Big-Data-Analysis/
│
├── 📄 big_data_analysis.py      ← Main Python script (Dask-powered)
├── 📊 hospital_data.csv         ← Dataset (10,000 patients × 31 columns)
├── 📁 outputs/                  ← Auto-generated after running script
│   ├── hospital_big_data_dashboard.png
│   ├── department_analysis.csv
│   ├── payment_mode_analysis.csv
│   ├── age_group_analysis.csv
│   └── monthly_trend.csv
└── 📝 README.md
```

---

## 📊 Dataset Description

**File:** `hospital_data.csv`
**Records:** 10,000 rows | **Columns:** 31

| Column | Description |
|--------|-------------|
| `patient_id` | Unique patient ID (PAT00001…) |
| `admission_date` | Date of hospital admission (2021–2023) |
| `discharge_date` | Date of discharge |
| `month` | Month name (Jan–Dec) |
| `quarter` | Quarter (Q1–Q4) |
| `year` | Year (2021, 2022, 2023) |
| `hospital` | Hospital name (AIIMS, Apollo, Fortis, etc.) |
| `department` | Medical department (Cardiology, Oncology, etc.) |
| `diagnosis` | Primary diagnosis |
| `admission_type` | Emergency / Elective / Routine / Referral |
| `patient_age` | Patient age (1–85) |
| `patient_gender` | Male / Female |
| `blood_group` | Blood group (A+, B+, O+, etc.) |
| `state` | Patient's home state |
| `length_of_stay_days` | Number of days admitted |
| `bed_type` | General / Semi-Private / Private / ICU |
| `icu_days` | Days spent in ICU |
| `doctor_visits` | Number of doctor visits |
| `tests_conducted` | Number of tests done |
| `surgeries` | Number of surgeries performed |
| `medicine_cost` | Medicine expenses (₹) |
| `doctor_fee` | Doctor consultation fees (₹) |
| `lab_cost` | Laboratory test costs (₹) |
| `room_cost` | Room/bed charges (₹) |
| `total_bill` | Total hospital bill (₹) |
| `payment_mode` | Insurance / Cash / Government Scheme / Corporate |
| `insurance_covered` | Amount covered by insurance (₹) |
| `out_of_pocket` | Amount paid by patient (₹) |
| `patient_status` | Discharged / Under Treatment / ICU / Transferred / Deceased |
| `readmission_flag` | 1 = Readmitted within 30 days, 0 = No |
| `satisfaction_score` | Patient satisfaction score (2.0–5.0) |

---

## 🛠️ Tools & Libraries Used

| Library | Purpose |
|---------|---------|
| **Dask** | Scalable parallel big data processing |
| **Pandas** | Data manipulation and aggregation |
| **Matplotlib** | Charts and visualizations |
| **Seaborn** | Statistical heatmaps and plots |

---

## 🔧 How to Run

### Step 1 — Install dependencies
```bash
pip install dask pandas matplotlib seaborn pyarrow
```

### Step 2 — Run the script
```bash
python big_data_analysis.py
```

### Step 3 — View outputs
All charts and summary CSVs are saved automatically in the `outputs/` folder.

---

## 📈 Key Insights

1. **10,000 patient records** processed in parallel using Dask partitions
2. **Cardiology & Oncology** generate the highest hospital revenue
3. **Insurance** is the most common payment mode
4. **Senior patients (61+)** have the longest average hospital stay
5. **Emergency admissions** account for the highest average bill
6. Readmission rate is under **25%** — indicates good treatment quality
7. **ICU patients** have significantly higher bills than general ward patients
8. Dask's partitioned processing scales to **millions of records** without code changes

---

## 🔑 Why Dask for Big Data?

| Feature | Pandas | Dask |
|---------|--------|------|
| Dataset Size | Limited by RAM | Larger than RAM ✅ |
| Processing | Single-core | Multi-core Parallel ✅ |
| API | Standard | Pandas-compatible ✅ |
| Lazy Evaluation | ❌ | ✅ |
| Scalability | Low | Cluster-scale ✅ |

---

<div align="center">
<b>CODTECH IT Solutions Pvt. Ltd.</b> — Data Analytics Internship — Task 1
</div>
