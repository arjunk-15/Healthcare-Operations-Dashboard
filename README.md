# Healthcare Operations Dashboard | Python & Power BI

## Project Overview

The Healthcare Operations Dashboard is an end-to-end data analytics project designed to analyze hospital operations, patient admissions, bed utilization, waiting times, and staff availability.

The project uses **synthetic hospital data** representing operations during 2025. Python is used for data cleaning, integration, validation, and exploratory data analysis (EDA), while Power BI is used to develop interactive dashboards.

## Project Objectives

- Analyze monthly and department-wise patient admissions.
- Measure average patient length of stay.
- Evaluate hospital bed occupancy rates.
- Identify departments with longer patient waiting times.
- Monitor staff availability across departments and shifts.
- Present operational insights through interactive Power BI visualizations.

## Tools and Technologies

| Technology | Purpose |
|---|---|
| Python | Data processing and analysis |
| Pandas | Data cleaning, merging, and aggregation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Exploratory analysis |
| Google Colab | Python development environment |
| Power BI | Interactive dashboard development |
| DAX | KPI calculations |

## Dataset

The project uses synthetic data covering five hospital departments:

- Emergency
- Cardiology
- Neurology
- Orthopedics
- General Medicine

The datasets include patient admissions, waiting times, bed occupancy, staff details, and staff schedules.

### Dataset Summary

| Dataset | Records |
|---|---:|
| Admissions | 5,000 |
| Patient Waiting Time | 5,000 |
| Daily Bed Occupancy | 1,825 |
| Staff Details | 150 |
| Staff Schedule | 32,808 |

## Project Workflow

### 1. Data Generation
Created synthetic hospital datasets covering admissions, waiting times, daily bed occupancy, and staff scheduling.

### 2. Data Cleaning
- Checked missing values and duplicates.
- Standardized date and time columns.
- Validated admission and discharge dates.
- Verified waiting-time calculations.
- Checked bed capacity and occupancy consistency.

### 3. Data Integration
- Integrated admissions and waiting-time records using `Admission_ID`.
- Integrated staff details and schedules using `Staff_ID`.
- Created daily hospital operations summaries.

### 4. Exploratory Data Analysis
Analyzed monthly admissions, department-wise admissions, average length of stay, patient waiting times, bed occupancy, and staff availability.

### 5. Power BI Dashboard
Developed dashboard pages containing KPI cards, department comparisons, monthly trends, and operational performance visualizations.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Admissions | 5,000 |
| Unique Patients | 4,400 |
| Average Length of Stay | 3.53 days |
| Average Waiting Time | 47.03 minutes |
| Bed Occupancy Rate | 27.20% |
| Staff Availability Rate | 94.14% |

## Key Findings

- Cardiology recorded the highest number of admissions.
- Emergency recorded the longest average patient waiting time.
- Average length of stay was relatively similar across departments.
- Overall bed occupancy was 27.20%.
- Staff availability across scheduled shifts was 94.14%.
- Monthly admissions fluctuated, with a substantial decline toward December.

## Dashboard Features

**Hospital Overview**
- Total admissions
- Unique patients
- Average length of stay
- Average waiting time
- Bed occupancy rate
- Staff availability rate
- Monthly admissions trend
- Department-wise admissions

**Operational Analysis**
- Department-wise waiting times
- Department-wise bed occupancy
- Department-wise staff availability

## Limitations

- All records are synthetic and do not represent an actual hospital.
- Operational patterns may reflect assumptions used during data generation.
- The sharp decline in December admissions should not be interpreted as a real seasonal trend without further validation.
- The dashboard is intended for analytics demonstration rather than clinical decision-making.

## Future Enhancements

- Patient admission forecasting
- Real-time hospital data integration
- Advanced staff workload analysis
- Hospital capacity planning
- Interactive date and department filtering

## Conclusion

This project demonstrates an end-to-end healthcare analytics workflow, from dataset preparation and validation to exploratory analysis and Power BI dashboard development.

It highlights practical skills in Python, Pandas, data integration, KPI development, DAX, and business intelligence reporting.
