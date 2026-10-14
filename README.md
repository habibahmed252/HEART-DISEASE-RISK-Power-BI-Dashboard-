# Heart Disease Risk
**Power BI Dashboard | Health Data Analytics**

## Project Overview

Heart Disease Risk is an interactive Power BI dashboard designed to explore how medical indicators, cardiovascular measurements, and lifestyle habits vary between patients with and without heart disease.

The dashboard brings patient-level health data into a set of focused report pages, helping users explore patterns, compare groups, and identify factors that may deserve further investigation.

This project focuses on data analysis and visualization. It is not a diagnostic tool, does not predict an individual's medical outcome, and should not be used as a substitute for professional medical advice.

## Dashboard Demo

[Watch the Dashboard Demo on YouTube](https://youtu.be/MwlUmarrXiM)

## About the Data

The **Heart Disease Risk Dataset** contains patient-level health information covering demographic characteristics, medical measurements, cardiovascular indicators, and lifestyle factors.

The analysis covers:

- Patient demographics
- Blood pressure and medical measurements
- Cholesterol and blood sugar indicators
- Heart-related indicators
- Lifestyle and behavioral factors

**Dataset:** Heart Disease Risk Dataset  
**Analysis Tool:** Microsoft Power BI  
**Purpose:** Explore patterns and differences between patients with and without heart disease and provide data-driven insights.

**Important Note:** This dashboard is intended for data analysis and educational purposes. It does not provide medical diagnosis or medical advice.

## Dashboard Preview

### Home Page

![Home Page](https://github.com/user-attachments/assets/d4dce6ab-da34-44fe-8ed4-ac9663a64b98)

### Overview

![Overview](https://github.com/user-attachments/assets/ca96475a-60d2-446e-8d18-f6c85b913122)

### Heart Indicators

![Heart Indicators](https://github.com/user-attachments/assets/9be56275-08b5-41a1-98c7-553d627e1ed6)

### Medical Risks & Health Indicators

![Medical Risks & Health Indicators](https://github.com/user-attachments/assets/a57f270e-2ff3-485e-88ad-9fb293b61b5a)

### Lifestyle

![Lifestyle](https://github.com/user-attachments/assets/bf1aa0f9-0b46-458b-8d61-4d070a5d59bf)

---

## Project Objectives

- Explore the distribution of heart disease cases in the dataset.
- Compare key medical indicators between patients with and without heart disease.
- Examine cardiovascular measurements, including heart rate and ST depression.
- Review blood pressure, blood sugar, HbA1c, and lipid-profile measurements.
- Explore lifestyle variables such as stress, physical activity, sleep, diet, smoking, and alcohol consumption.
- Provide interactive filtering so users can investigate different patient groups.
- Present findings in a clear visual format that supports exploratory analysis.

## Dataset Overview

Fields represented in the dashboard include:

| Category | Fields |
|---|---|
| Patient & Demographics | `patient_id`, `age`, `sex` |
| Heart Disease Outcome | `has_heart_disease` |
| Cardiovascular Measurements | `resting_heart_rate`, `max_heart_rate_achieved`, `st_depression` |
| Blood Pressure | `resting_bp_systolic`, `resting_bp_diastolic` |
| Blood Markers | `cholesterol_total`, `hdl`, `ldl`, `triglycerides`, `fasting_blood_sugar`, `hba1c` |
| Body Measurement | `bmi` |
| Symptoms & Related Indicators | `chest_pain_type`, `exercise_induced_angina` |
| Medical History | `family_history` |
| Lifestyle Factors | `smoker_status`, `alcohol_units_per_week`, `exercise_minutes_per_week`, `sleep_hours`, `stress_score`, `diet_quality_score` |

Additional fields available in the dataset may include wearable ownership and daily activity information.

The dashboard uses the fields relevant to each visual. Dataset source, row count, and preprocessing details should be documented only after verification.

## Tools & Techniques

- Microsoft Power BI
- Data Visualization
- Exploratory Data Analysis (EDA)
- KPI Cards
- Bar Charts and Column Charts
- Scatter Plots
- Percentage-Stacked Charts
- Interactive Slicers and Cross-Filtering
- Report Navigation
- Help Tooltips

---

## Dashboard Pages & Key Insights

### 1. Home Page

**Purpose**

The landing page introduces the dashboard and provides navigation to the analysis sections.

**What it offers**

- A visual entry point to the report.
- Navigation to the main dashboard pages.
- A consistent theme for the report experience.

**Key Takeaway**

The Home page helps users understand the dashboard structure and move directly to the area they want to explore.

### 2. Overview

**Purpose**

This page provides a high-level snapshot of the patient population and the heart disease outcome.

**Main Visuals & Questions**

- **Total Patients:** How many patient records are included in the current filter context?
- **Heart Disease Rate:** What proportion of the currently selected population has heart disease?
- **Average Cholesterol:** What is the average total cholesterol level in the selected population?
- **Average BMI:** What is the average body mass index in the selected population?
- **Heart Disease Prevalence by Age:** How does the observed prevalence vary across age groups?
- **Patient Distribution by Family History:** How are patients distributed by family-history status?
- **Patient Distribution by Smoking Status:** How are patients distributed across smoking categories?

**Key Insights**

- The heart disease rate should be interpreted alongside the total number of patients currently selected.
- The age-group comparison helps identify whether observed prevalence differs across age segments.
- Family history and smoking status provide population-level context, but the charts alone do not establish causation.
- Average cholesterol and BMI summarize the selected population; averages can hide differences within subgroups.

### 3. Heart Indicators

**Purpose**

This page compares cardiovascular measurements and symptom-related indicators between patients with and without heart disease.

**Main Visuals & Questions**

- **Average Resting Heart Rate:** Is there a difference in average resting heart rate between the two groups?
- **Average Maximum Heart Rate:** How does the average achieved maximum heart rate compare between the groups?
- **Average ST Depression:** How does ST depression differ by heart disease status?
- **Heart Disease Cases:** What is the count or rate shown by the relevant KPI in the current filter context?
- **Maximum Heart Rate vs. ST Depression:** How do these two measurements interact across the two groups?
- **Chest Pain Type & Heart Disease:** How does the proportion of heart disease cases vary across reported chest-pain categories?
- **Heart Disease by Exercise-Induced Angina:** How does heart disease status vary according to exercise-induced angina?

**Key Insights**

- Compare the two heart disease groups across resting heart rate, maximum heart rate, and ST depression rather than interpreting any single measurement in isolation.
- The scatter plot can reveal clusters, overlap, and outliers that may be hidden by averages.
- Differences across chest-pain categories may highlight groups with different observed outcome distributions.
- Exercise-induced angina is a symptom-related variable worth exploring, but this descriptive dashboard cannot determine whether it causes heart disease.

### 4. Medical Risks & Health Indicators

**Purpose**

This page focuses on blood pressure, blood sugar, HbA1c, BMI, and lipid-profile measurements.

**Main Visuals & Questions**

- **Average HbA1c:** What is the average HbA1c level in the selected population?
- **Average LDL:** What is the average LDL
