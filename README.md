# 🏥 CODTECH IT Solutions — Data Analytics Internship
## Task 1: Big Data Analysis
### Project: 🏥 Hospital Patient Records — Big Data Analysis using Dask

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Dask](https://img.shields.io/badge/Dask-Big%20Data-EF7C35?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Healthcare](https://img.shields.io/badge/Domain-Healthcare%20Analytics-brightgreen?style=for-the-badge)

</div>

---

## 📋 Internship Details

| Field | Details |
|-------|---------|
| **Name** | Kamal Lochan Mishra |
| **Company** | CODTECH IT Solutions Pvt. Ltd. |
| **Intern ID** | CTIS05S1 |
| **Domain** | Data Analytics |
| **Duration** | 4 Weeks |
| **Mentor** | Neela Santhosh Kumar |
| **Task** | Task 1 — Big Data Analysis |

---

## 🎯 Project Overview

> Perform **Big Data Analysis** on a large hospital patient dataset (**10,000 records × 31 columns**) using **Dask** for scalable parallel processing. Derive actionable healthcare insights on revenue, departments, patient demographics, admission trends, and treatment patterns.

This project demonstrates that Dask-based code scales from thousands to **millions of rows** on distributed clusters without any code changes — proving true Big Data scalability.

---

## 🗂️ Project Structure

```
Task-1-Big-Data-Analysis/
│
├── 📓 big_data_analysis.ipynb       ← Main Jupyter Notebook (Dask-powered)
├── 📊 hospital_data.csv             ← Dataset (10,000 patients × 31 columns)
└── 📝 README.md
```

---

## 📊 Dataset Description

**File:** `hospital_data.csv`
**Records:** 10,000 rows | **Columns:** 31

### Column Reference

| Column | Type | Description |
|--------|------|-------------|
| `patient_id` | str | Unique patient ID (PAT00001…) |
| `admission_date` | date | Date of hospital admission (2021–2023) |
| `discharge_date` | date | Date of discharge |
| `month` | str | Month name (Jan–Dec) |
| `quarter` | str | Quarter (Q1–Q4) |
| `year` | int | Year (2021, 2022, 2023) |
| `hospital` | str | Hospital name (AIIMS, Apollo, Fortis, etc.) |
| `department` | str | Medical department (Cardiology, Oncology, etc.) |
| `diagnosis` | str | Primary diagnosis |
| `admission_type` | str | Emergency / Elective / Routine / Referral |
| `patient_age` | int | Patient age (1–85 years) |
| `patient_gender` | str | Male / Female |
| `blood_group` | str | Blood group (A+, B+, O+, etc.) |
| `state` | str | Patient's home state |
| `length_of_stay_days` | int | Number of days admitted |
| `bed_type` | str | General / Semi-Private / Private / ICU |
| `icu_days` | int | Days spent in ICU |
| `doctor_visits` | int | Number of doctor visits |
| `tests_conducted` | int | Number of tests done |
| `surgeries` | int | Number of surgeries performed |
| `medicine_cost` | float | Medicine expenses (₹) |
| `doctor_fee` | float | Doctor consultation fees (₹) |
| `lab_cost` | float | Laboratory test costs (₹) |
| `room_cost` | float | Room/bed charges (₹) |
| `total_bill` | float | Total hospital bill (₹) |
| `payment_mode` | str | Insurance / Cash / Government Scheme / Corporate |
| `insurance_covered` | float | Amount covered by insurance (₹) |
| `out_of_pocket` | float | Amount paid by patient (₹) |
| `patient_status` | str | Discharged / Under Treatment / ICU / Transferred / Deceased |
| `readmission_flag` | int | 1 = Readmitted within 30 days, 0 = No |
| `satisfaction_score` | float | Patient satisfaction score (2.0–5.0) |

---

## 🛠️ Tools & Libraries Used

| Library | Version | Purpose |
|---------|---------|---------|
| **Dask** | Latest | Parallel big data processing |
| **Pandas** | 1.5+ | Data manipulation & aggregation |
| **NumPy** | 1.23+ | Numerical operations |
| **Matplotlib** | 3.6+ | Charts & visualizations |
| **Seaborn** | 0.12+ | Statistical plots |

---

## 🔧 How to Run

### Step 1 — Install dependencies
```bash
pip install dask pandas numpy matplotlib seaborn jupyter
```

### Step 2 — Clone or download this repository
```
Task-1-Big-Data-Analysis/
├── big_data_analysis.ipynb
├── hospital_data.csv
└── README.md
```

### Step 3 — Open the Jupyter Notebook
```bash
jupyter notebook big_data_analysis.ipynb
```

### Step 4 — Run all cells
**Kernel → Restart & Run All**

---

## 📓 Jupyter Notebook Structure

The notebook contains multiple analysis sections including:
- Environment setup & library imports
- Dataset loading with Dask (parallel read)
- Data quality checks
- Department-wise analysis
- Payment mode breakdown
- Age group insights
- Monthly & quarterly trends
- Visualizations (charts, heatmaps, distributions)
- Key findings summary

---

## 📈 Key Insights

1. **10,000 patient records** processed in parallel using Dask partitions
2. **Cardiology & Oncology** departments generate the highest hospital revenue
3. **Insurance** is the most common payment mode across all segments
4. **Senior patients (61+)** have the longest average hospital stay
5. **Emergency admissions** account for the highest average bill amount
6. **Readmission rate** is under **25%** — indicates good treatment quality
7. **ICU patients** have significantly higher bills than general ward patients
8. Dask's partitioned processing scales to **millions of records** without code changes

---

## 🔑 Why Dask for Big Data?

| Feature | Pandas | Dask |
|---------|--------|------|
| Max Dataset Size | Limited by RAM | Larger than RAM ✅ |
| Processing | Single-core | Multi-core Parallel ✅ |
| API | Standard | Pandas-compatible ✅ |
| Lazy Evaluation | ❌ | ✅ |
| Scalability | Low | Cluster-scale ✅ |

---

<div align="center">

**CODTECH IT Solutions Pvt. Ltd.** — Data Analytics Internship — Task 1

Made with ❤️ for Healthcare Analytics 🏥📊

</div>
