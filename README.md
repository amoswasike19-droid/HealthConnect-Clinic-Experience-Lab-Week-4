HealthConnect Clinic Experience Lab – Week 4

Project Overview

HealthConnect Clinic is a fictional healthcare provider experiencing challenges related to missed appointments, inefficient use of appointment slots, and repetitive appointment enquiries.

The central project question is:

How can HealthConnect Clinic use data and AI to reduce missed appointments and improve the patient support experience?

As part of the AnalystLab Africa Experience Lab Internship, this Week 4 project focuses on the Data Analytics track and establishes the foundation for analysing appointment attendance and no-show patterns.

Week 4 Objectives

The main objectives of Week 4 were to:

- Understand the HealthConnect business problem.
- Review the appointment dataset and Data Dictionary.
- Assess the initial quality and suitability of the data.
- Identify variables relevant to appointment attendance and no-shows.
- Define relevant business questions.
- Propose meaningful KPIs.
- Develop an initial analytical approach.
- Identify assumptions, limitations, risks, and dependencies.

Dataset

The HealthConnect Appointment Dataset contains 5,000 appointment records and 18 variables.

The variables cover:

- Patient demographics
- Appointment details
- Booking information
- Previous appointment history
- Reminder information
- Distance to the clinic
- Waiting time
- Appointment outcomes

The primary outcome variable is "appointment_outcome", which contains:

- Attended
- No-Show
- Cancelled

The Data Dictionary was used to understand the meaning, data type, and usage of the variables.

Data Quality Assessment

An initial assessment found the dataset suitable for further analysis.

Key observations include:

- "appointment_id" is the primary key.
- "patient_id" may appear across multiple appointments.
- The dataset contains appropriate numerical, date, and categorical variables.
- "distance_to_clinic_km" and "waiting_time_minutes" contain limited missing values and will require attention during data preparation.
- "previous_no_shows" cannot exceed the number of previous appointments.
- "reminder_channel" is recorded as "None" when no reminder was sent.

Business Questions

The initial analysis will investigate questions such as:

1. What factors are associated with patients missing their scheduled appointments?
2. Does previous no-show history relate to current appointment attendance?
3. Does sending appointment reminders affect attendance?
4. Does booking lead time influence the likelihood of a no-show?
5. Are no-show patterns different across appointment types, age groups, appointment days, or appointment times?
6. Does distance to the clinic have an association with appointment attendance?
7. Is waiting time associated with appointment outcomes?

Proposed KPIs

Five potential KPIs were identified:

1. Appointment No-Show Rate – measures the overall missed-appointment problem.
2. Reminder Effectiveness Rate – assesses the relationship between reminders and attendance.
3. Previous No-Show Rate – examines the relationship between previous missed appointments and current attendance.
4. Average Booking Lead Time – assesses the relationship between booking lead time and no-shows.
5. No-Show Rate by Appointment Type – identifies appointment categories that may require additional attention.

These KPIs are proposed for subsequent analysis and have not been calculated at the Week 4 stage.

Initial Analysis Approach

The planned analytical process is to:

1. Prepare and validate the data.
2. Explore appointment outcomes.
3. Investigate factors associated with no-shows.
4. Calculate and analyse the proposed KPIs in later stages.
5. Use SQL for data exploration and analytical queries.
6. Use Power BI for subsequent KPI analysis and visualisation.
7. Identify actionable patterns while distinguishing association from causation.

Assumptions and Limitations

The analysis assumes that appointment outcomes, booking information, previous appointment history, and reminder information are accurately recorded.

Key limitations include:

- The dataset is fictional and anonymized.
- Not every factor influencing attendance may be captured.
- Association between variables does not necessarily establish causation.
- Reminder data does not confirm whether a patient received, read, or acted upon a reminder.

Week 4 Outcome

Week 4 established a structured analytical foundation for the HealthConnect project. The business problem, relevant data, business questions, proposed KPIs, analytical approach, and key project considerations have been defined.

Week 5 Focus

The proposed Week 5 focus is to move from problem understanding into practical data exploration and analysis.

Planned activities include:

- Calculating the proposed KPIs.
- Investigating appointment outcome patterns.
- Comparing no-show patterns across relevant variables.
- Developing evidence-based findings.
- Preparing insights that can support the broader HealthConnect project.

Tools

- Excel / Power Query
- SQL
- Power BI
- GitHub

Project Status

Week 4: Completed – Problem Understanding & Initial Analysis Planning

Next Stage: – Data Exploration & Analysis
