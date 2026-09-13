# HealthConnect Appointment Analysis

## Project Overview

HealthConnect Clinic is a fictional healthcare provider experiencing challenges with missed patient appointments and patient support.

This project explores how data analytics can help HealthConnect understand appointment attendance and no-show patterns and provide insights that can support better decision-making and patient engagement.

This project is being developed as part of the **AnalystLab Africa Experience Lab Programme**.

## Project Question

> How can HealthConnect Clinic use data and AI to reduce missed appointments and improve the patient support experience?

## My Role

As a **Data Analytics intern**, my role is to investigate the appointment data and identify patterns that may be associated with patient attendance and missed appointments.

The analysis will provide a foundation for deeper analysis and data-driven recommendations in subsequent stages of the project.

## Week 4 Focus

During Week 4, I focused on understanding the HealthConnect business problem and preparing the foundation for the analysis.

### Activities Completed

- Reviewed the HealthConnect business scenario
- Reviewed the appointment dataset
- Reviewed the data dictionary
- Assessed the initial quality of the dataset
- Identified variables relevant to appointment attendance and no-shows
- Defined business questions to guide future analysis
- Proposed potential KPIs linked to the business questions
- Developed an initial analysis approach
- Documented assumptions, limitations, risks, and dependencies

## Dataset Overview

The HealthConnect appointment dataset contains **5,000 appointment records and 18 variables**.

The dataset includes information relating to:

- Patient demographics
- Appointment details
- Booking information
- Previous appointment history
- Previous no-shows
- Appointment reminders
- Distance to the clinic
- Waiting time
- Appointment outcomes

### Initial Data Quality Findings

The initial assessment identified:

- 5,000 appointment records
- 18 variables
- 0 completely duplicated records
- 5,000 unique appointment IDs
- 1,696 unique patient IDs
- Missing values in `reminder_channel`
- Missing values in `distance_to_clinic_km`
- Missing values in `waiting_time_minutes`

Further investigation will be carried out before making decisions about how these missing values should be handled.

## Key Business Questions

The analysis will explore questions such as:

1. What proportion of scheduled appointments result in no-shows?
2. Is there a relationship between appointment reminders and patient attendance?
3. Does the reminder channel appear to be associated with different attendance outcomes?
4. Which patient or appointment characteristics are associated with higher no-show rates?
5. Is booking lead time associated with appointment attendance?
6. Does previous no-show behaviour appear to be associated with future no-shows?
7. Are appointment day and time associated with attendance patterns?
8. Is distance to the clinic associated with no-shows?

## Proposed KPIs

The following KPIs have been identified for subsequent stages of the project:

- **No-Show Rate**
- **Attendance Rate**
- **Reminder Effectiveness Rate**
- **No-Show Rate by Appointment Type**
- **Repeat No-Show Rate**

These KPIs have been proposed to help measure appointment attendance and investigate factors that may contribute to missed appointments.

## Tools

- Python
- Pandas
- Jupyter Notebook
- VS Code

## Project Status

**Current Stage: Week 4 — Problem Understanding and Initial Analysis**

The project is currently at the foundation stage. Detailed exploratory analysis, KPI calculations, visualizations, and recommendations will be developed in subsequent stages.

## Next Steps

The next stage of the project will focus on:

- Preparing the data for analysis
- Investigating appointment attendance and no-show patterns
- Analysing the proposed KPIs
- Exploring relationships between relevant variables
- Developing data-driven insights
- Providing recommendations to support improved appointment attendance

## Disclaimer

HealthConnect Clinic and its appointment dataset are fictional resources provided for the AnalystLab Africa Experience Lab. The data does not represent real patients or a real healthcare provider.

## Week 5 — HealthConnect Appointment Analytics

### Overview

Week 5 focused on moving the HealthConnect project from initial data exploration into practical data analytics. The appointment dataset was prepared and analysed to identify patterns in appointment attendance and no-show behaviour.

The analysis was conducted using **Python and Jupyter Notebook**, with the findings presented through an interactive **Power BI dashboard**.

### Objectives

The main objectives for Week 5 were to:

* Prepare and assess the HealthConnect appointment dataset
* Conduct exploratory data analysis (EDA)
* Calculate key appointment attendance and no-show KPIs
* Identify patterns associated with appointment no-shows
* Create meaningful data visualisations
* Develop business insights and recommendations
* Document assumptions and limitations
* Present the findings through a Power BI dashboard

### Data Preparation

The HealthConnect appointment dataset contains **5,000 appointment records and 18 variables**.

The data preparation process included:

* Reviewing the structure and data types of the dataset
* Checking for missing values
* Checking for duplicate records
* Reviewing categorical and numerical variables
* Assessing appointment outcomes
* Creating an analytical dataset for attendance and no-show analysis

Cancelled appointments were excluded from the primary attendance and no-show analysis because cancellation represents a different outcome from an appointment where a patient did not attend.

### Exploratory Data Analysis

The EDA examined appointment attendance and no-show behaviour across several areas, including:

* Appointment type
* Reminder status
* Reminder channel
* Previous no-show history
* Booking lead time
* Appointment day
* Age group
* Gender

The analysis was used to identify patterns that could support HealthConnect's appointment management and patient engagement strategies.

### Key Performance Indicators

The following KPIs were calculated:

* **Eligible Appointments**
* **Attended Appointments**
* **No-Show Appointments**
* **Attendance Rate**
* **No-Show Rate**
* **Reminder Effectiveness**
* **Repeat No-Show Rate**

These KPIs provide a high-level view of appointment attendance performance and help identify areas requiring further attention.

### Power BI Dashboard

An interactive Power BI dashboard was developed to communicate the Week 5 findings.

The dashboard includes:

* KPI cards for appointment performance
* No-show rate by appointment type
* No-show rate by reminder status
* No-show rate by reminder channel
* No-show rate by previous no-show history
* No-show rate by booking lead time
* Interactive filters for exploring the data

The dashboard is designed to make the analysis easier for stakeholders to understand and use when monitoring appointment attendance.

### Recommendations

Based on the analysis, the project recommends:

1. Strengthening appointment reminder strategies, particularly for groups with higher no-show rates.
2. Giving additional attention to patients with previous no-show behaviour.
3. Reviewing appointment categories associated with comparatively higher no-show rates.
4. Considering booking lead time when planning reminder and patient-engagement activities.
5. Continuing to monitor attendance and no-show KPIs through an interactive analytics dashboard.

### Limitations

The analysis has several limitations:

* The dataset represents the available HealthConnect appointment records and may not represent all real-world patient or operational conditions.
* Some variables contain missing values, including reminder channel, distance to clinic, and waiting time.
* Cancelled appointments were excluded from the primary no-show analysis.
* Observed relationships represent associations and should not automatically be interpreted as causal relationships.
* The analysis is primarily descriptive and exploratory rather than a predictive model of individual patient behaviour.

### Tools Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **Microsoft Power BI**
* **Microsoft Excel**

### Week 5 Deliverables

The Week 5 project outputs include:

* `HealthConnect_Week5_Analytics.ipynb` — Jupyter Notebook containing the data preparation, EDA, KPI analysis, visualisations, findings, recommendations and limitations.
* `HealthConnect_Week5_Dashboard.pbix` — Interactive Power BI dashboard presenting the key appointment analytics.
* HealthConnect appointment dataset and relevant supporting files.

### Next Steps — Week 6

The next stage of the project will focus on refining the analytics and dashboard, incorporating feedback, strengthening the recommendations, and continuing development of the HealthConnect project.

Week 6 – Advanced Analytics & Decision Support

In Week 6, I built on my Week 5 work by going deeper into the HealthConnect appointment data.

What I worked on

- Analysed booking lead time and previous no-shows.
- Looked at appointment types, times, and reminder patterns.
- Validated key attendance and no-show KPIs.
- Improved the Power BI dashboard.
- Identified key findings that can support better decision-making.

Key Findings

The analysis showed useful patterns around previous no-shows, booking lead time, reminders, and appointment types.

Recommendations

The findings can help HealthConnect focus reminders and patient engagement on higher-risk appointment groups.

Week 7 Focus

Next, I will support testing, validation, and cross-track integration of the Data Analytics outputs.

