# PBJ Daily Nurse Staffing Analysis

### Overview
This project is a case study analyzing staffing and quality data for long-term care facilities using python in jupyter notebook.
The goal is to provide actionable insights that will help improve resource allocation, staffing levels, and ultimately the quality of care for residents in nursing homes.

### Datasets

1. PBJ Daily Nurse Staffing Dataset

    - Contains detailed staffing hours across different nursing roles (e.g., RN, LPN, CNA, MedAide) for various long-term care facilities.
    - Includes facility information (PROVNUM, PROVNAME, CITY, STATE) and resident census (MDScensus).
    - Reporting period: Q2 2024.
   
2. MDS Quality Measures Dataset

    - Focuses on quality measures for long-term care, including data on resident safety (e.g., falls with major injury).

### Objective

The objective of this analysis is to identify staffing gaps, optimize resource allocation, and support strategic decision-making for the sales leadership team. By leveraging the [Payroll-Based Journal (PBJ) Daily Nurse Staffing](https://data.cms.gov/quality-of-care/payroll-based-journal-daily-nurse-staffing/data) dataset and the [MDS Quality Measures](https://data.cms.gov/provider-data/dataset/djen-97ju) dataset, this analysis aims to enhance operational efficiency and improve resident care.

### Files in this repository

 -     case_study.ipynb – The Jupyter Notebook containing the full analysis, including data cleaning, visualization, and insights.

### Key Insights
- **Staffing Gaps in High-Resident Facilities**: Some facilities with high resident counts exhibit low staffing hours, indicating potential understaffing.
- **MedAide Staffing Shortages**: Facilities with high resident counts often have insufficient MedAide staffing, suggesting a need for targeted recruitment.
- **Heavy Reliance on Contract Workers**: Some facilities depend heavily on contractors, which may affect continuity and quality of care.
- **Regional Staffing Disparities**: New York (NY) has significant differences in staffing patterns, potentially indicating overcrowding or inefficiency.
- **Impact of Training on Resident Safety**: A weak negative correlation between nurse aide training and resident safety, suggesting training could improve care outcomes.


