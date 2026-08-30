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
