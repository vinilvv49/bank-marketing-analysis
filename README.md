**Bank Marketing Campaign Analysis**

A complete data-cleaning, analysis and insight-generation project based on the Bank Marketing Dataset (UCI Repository).

**Repository Structure**
/
├── bankfull.csv              → Dataset used in the project
├── My_Final_Project.pdf       → Full analysis report
├── README.md                  → Project documentation

**Project Overview**

This project analyzes customer and campaign data from a Portuguese bank to determine which factors influence whether a customer subscribes to a term deposit.

The work includes:

Data loading & exploration

Data cleaning and preprocessing

Feature engineering

Visual analysis

Statistical summaries

Insight generation

Strategic recommendations

**Dataset Details**

File: bankfull.csv

Records: 45,211

Columns: 17 original

Source: UCI Machine Learning Repository

Target Variable: y → subscription (yes/no)

**Key Features**

Demographic: age, job, marital, education

Financial: balance, loan, housing

Campaign-related: duration, contact, campaign, pdays, previous, poutcome

Engineered:

age_group

total_contacts

avg_call_duration

**Data Cleaning & Preparation**

Removed unusable unknown values (job, education, contact → replaced with mode)

Converted categorical columns to efficient category dtype

Renamed y to subscription

Added derived columns for deeper insight

Validated: 0 missing values, 0 duplicates

**Key Insights**

Customers aged 26–60 form the core target group.

Secondary education is most common.

Higher balance clients show significantly better subscription rates.

Call duration is the strongest positive conversion factor.

Customers with housing or personal loans show poor subscription behaviour.

Most conversions happen after meaningful, longer calls.

Peak campaign month: May.

**Recommendations**

Focus on high-balance, management, retired and technician customer groups.

Improve agent communication quality to increase call duration effectiveness.

Reduce over-contacting; it reduces conversion chances.

Prioritize high-performing campaign months based on historical trends.

Use customer segmentation instead of blanket calling.

**Project Report**

Detailed step-by-step analysis with visuals:
My_Final_Project.pdf

Dataset used in the analysis:
bankfull.csv
