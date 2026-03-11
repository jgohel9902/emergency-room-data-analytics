# Healthcare Emergency Room Analytics with Python

## Project Overview
This project performs an end-to-end data analytics workflow on hospital emergency room data using Python. The goal of the analysis is to explore patient flow patterns, emergency room wait times, department referrals, patient demographics, and satisfaction scores to generate insights that could help improve hospital operational efficiency.

The project demonstrates a complete data analytics pipeline including data loading, cleaning, feature engineering, exploratory analysis, visualization, and basic machine learning.

---

## Objectives
The primary objectives of this project are:

- Load and inspect emergency room data using Python
- Perform data cleaning and preprocessing
- Standardize dataset fields and validate data types
- Create additional analytical features for time-based analysis
- Explore patient demographics and admission patterns
- Analyze emergency room waiting times
- Investigate department referral trends
- Evaluate patient satisfaction relationships
- Identify peak emergency room demand periods
- Perform patient segmentation using machine learning techniques
- Generate operational insights and recommendations

---

## Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Scikit-learn  
Jupyter Notebook  

---

## Project Structure


Healthcare-ER-Analytics-Python
│
├── data
│ ├── Hospital ER_Data.csv
│ └── cleaned_er_dataset.csv
│
├── notebooks
│ └── healthcare_er_analysis.ipynb
│
├── images
│
├── reports
│
├── requirements.txt
└── README.md


---

## Dataset Description

The dataset contains emergency room patient visit records including:

- Patient ID
- Patient Admission Date
- Patient Gender
- Patient Age
- Patient Race
- Department Referral
- Admission Flag
- Patient Satisfaction Score
- Patient Wait Time

These variables allow analysis of hospital workload, patient demographics, operational performance, and service quality.

---

## Data Processing Steps

### Data Loading
The dataset was imported using Pandas and inspected to understand the structure, data types, and missing values.

### Data Cleaning
Column names were standardized by converting them to lowercase and replacing spaces with underscores. Duplicate records were checked and removed.

### Data Type Validation
Date columns were converted into datetime format to support time-based analysis. Numeric fields such as age, satisfaction score, and wait time were validated and converted where necessary.

### Feature Engineering
New analytical features were created from the admission timestamp including:

- admission_year
- admission_month
- admission_day
- admission_hour
- admission_day_name
- weekend indicator

Age groups were also created to analyze demographic segments.

---

## Exploratory Data Analysis

Several visualizations and analyses were performed including:

- Patient age distribution
- Gender distribution of patients
- Emergency room wait time distribution
- Average wait time by department
- Relationship between wait time and patient satisfaction
- Peak emergency room admission hours
- Emergency room visits by day of week
- Department referral distribution
- Average satisfaction score by department
- Average wait time by age group

These analyses helped reveal patterns in patient flow and hospital operations.

---

## Operational Performance Metrics

Key operational metrics calculated include:

- Total number of ER visits
- Average waiting time
- Average patient satisfaction score
- Average patient age
- Department referral workload

These metrics provide an overview of emergency room performance.

---

## Patient Segmentation (Machine Learning)

K-Means clustering was applied to identify patterns in patient characteristics using:

- Patient age
- Patient wait time
- Patient satisfaction score

The clustering model grouped patients into segments based on their visit characteristics, helping identify potential patterns in patient experience.

---

## Key Insights

- Emergency room admissions show clear peak hours indicating periods of high demand.
- Wait times vary significantly across hospital departments.
- Patient satisfaction appears to be influenced by waiting time.
- Some age groups experience different waiting patterns.
- Patient segmentation reveals different operational patterns across visits.

---

## Recommendations

Based on the analysis, the following recommendations can be made:

- Increase staffing during peak admission hours.
- Investigate departments with high waiting times to improve workflows.
- Monitor satisfaction scores in departments with lower ratings.
- Use demand patterns to improve scheduling and resource allocation.
- Analyze patient segments to better tailor hospital services.

---

## Conclusion

This project demonstrates how Python-based data analytics can be used to analyze healthcare operational data. Through data cleaning, visualization, statistical analysis, and machine learning, meaningful insights can be generated to support healthcare decision-making and improve emergency room efficiency.

---

## Author

Jenil Gohel  
Computer Programming and Analysis Student  
Conestoga College
2️⃣ Full Project Documentation (For PDF / Word)

Use this as a Word document or PDF report.

Title:

Healthcare Emergency Room Data Analytics Project
Introduction

Healthcare systems generate large volumes of operational data that can be analyzed to improve patient care and hospital efficiency. Emergency departments in particular experience high variability in patient demand, making it important to understand patterns in patient visits, waiting times, and department workload.

This project analyzes hospital emergency room data using Python to identify patterns in patient flow, waiting times, satisfaction levels, and referral departments. The goal of the project is to demonstrate how data analytics can be used to support operational decision-making in healthcare environments.

Project Objectives

The main objectives of the project include:

• Performing data cleaning and preprocessing
• Exploring patient demographic characteristics
• Analyzing waiting times and satisfaction scores
• Identifying peak admission hours and patient flow trends
• Evaluating department referral patterns
• Applying machine learning techniques for patient segmentation
• Generating actionable operational insights

Tools and Technologies

The following tools were used in the project:

Python
Pandas – Data manipulation and cleaning
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical visualizations
Scikit-learn – Machine learning algorithms
Jupyter Notebook – Interactive analysis environment

Dataset Description

The dataset contains emergency room patient records including:

Patient ID
Patient Admission Date
Patient Gender
Patient Age
Patient Race
Department Referral
Patient Admission Flag
Patient Satisfaction Score
Patient Wait Time

These variables allow analysis of hospital operational performance and patient experience.

Data Cleaning and Preparation

The first phase of the project involved cleaning and preparing the dataset.

Key tasks included:

• Standardizing column names
• Checking for duplicate records
• Identifying missing values
• Converting admission date to datetime format
• Converting numerical columns to proper numeric types

These steps ensured that the dataset was ready for further analysis.

Feature Engineering

Additional features were created from the admission timestamp to support time-based analysis.

These include:

Admission Year
Admission Month
Admission Day
Admission Hour
Day of Week
Weekend Indicator

Age groups were also created to analyze patient demographics.

Exploratory Data Analysis

Several visualizations were created to understand patient behavior and hospital operations.

Key analyses included:

• Age distribution of emergency room patients
• Gender distribution of patients
• Distribution of emergency room waiting times
• Average waiting time by department referral
• Relationship between wait time and satisfaction scores
• Peak emergency room admission hours
• Emergency room visits by day of week
• Average wait time by age group

These analyses helped identify patterns in emergency department operations.

Machine Learning: Patient Segmentation

K-Means clustering was applied to segment patients based on their visit characteristics.

Variables used for clustering included:

Patient Age
Patient Wait Time
Patient Satisfaction Score

This analysis helps identify groups of patients with similar experiences and patterns in emergency room visits.

Key Insights

The analysis revealed several important insights:

• Emergency room admissions show clear hourly demand patterns
• Certain departments experience higher patient loads than others
• Longer waiting times may influence patient satisfaction scores
• Patient demographics vary across emergency room visits
• Distinct patient groups exist based on waiting time and satisfaction levels

Challenges Encountered

During the project several challenges were encountered:

• Inconsistent column formatting in the raw dataset
• Date values stored as text instead of datetime format
• Some numeric fields initially imported as strings
• Missing values in certain categorical fields

These issues were resolved through proper data preprocessing techniques.

Recommendations

Based on the analysis, the following recommendations are suggested:

• Increase staffing during peak admission hours
• Improve workflow efficiency in departments with long wait times
• Monitor patient satisfaction trends regularly
• Use demand patterns to improve staff scheduling
• Investigate operational differences between patient segments

Conclusion

This project demonstrates how Python-based data analytics techniques can be used to analyze healthcare operational data. By combining data cleaning, visualization, statistical analysis, and machine learning, the project provides meaningful insights into emergency room operations.

The techniques used in this project can help healthcare administrators make data-driven decisions to improve hospital efficiency and patient experience.
