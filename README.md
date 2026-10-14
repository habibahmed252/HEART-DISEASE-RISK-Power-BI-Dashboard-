# Heart Disease Risk Analysis
**Power BI Dashboard | Health Data Analytics**

## Project Overview

Heart Disease Risk Analysis is an interactive data analysis dashboard designed to explore factors associated with heart disease across medical measurements, heart indicators, and lifestyle characteristics.

The dashboard allows users to explore patterns and differences between patients with and without heart disease through interactive visualizations, filters, and dedicated analysis pages.

**Analysis Tool:** Microsoft Power BI  
**Dataset:** Heart Disease Risk Dataset  
**Project Type:** Data Analysis & Visualization

## Dashboard Demo

[Watch the Dashboard Demo on YouTube](https://youtu.be/MwlUmarrXiM)

## About the Data

Heart Disease Risk Analysis is an interactive data analysis dashboard designed to explore factors associated with heart disease across medical measurements, heart indicators, and lifestyle characteristics.

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

## Dashboard Pages

### 1. Home Page

The landing page introduces the dashboard and provides navigation to the main analysis sections.

![Home Page](https://github.com/user-attachments/assets/d4dce6ab-da34-44fe-8ed4-ac9663a64b98)

### 2. Overview

**Purpose:** Provide a high-level summary of the patient population and heart disease status.

**Main Visuals**
- Total Patients
- Heart Disease Rate
- Average Cholesterol
- Average BMI
- Heart Disease Prevalence by Age
- Patient Distribution by Family History
- Patient Distribution by Smoking Status

**Analytical Focus**

This page provides an overview of the selected patient population and allows users to explore differences in heart disease prevalence across age groups and patient characteristics. KPI values should be interpreted in the context of the active filters.

![Overview](https://github.com/user-attachments/assets/ca96475a-60d2-446e-8d18-f6c85b913122)

### 3. Heart Indicators

**Purpose:** Explore cardiovascular measurements and symptom-related indicators across patients with and without heart disease.

**Main Visuals**
- Average Resting Heart Rate
- Average Maximum Heart Rate
- Average ST Depression
- Heart Disease Cases
- Maximum Heart Rate vs. ST Depression
- Chest Pain Type & Heart Disease
- Heart Disease by Exercise-Induced Angina

**Analytical Focus**

This page allows users to compare cardiovascular measurements between the two outcome groups, examine the relationship between maximum heart rate and ST depression, and explore how heart disease status varies across chest pain categories and exercise-induced angina.

![Heart Indicators](https://github.com/user-attachments/assets/9be56275-08b5-41a1-98c7-553d627e1ed6)

### 4. Medical Risks & Health Indicators

**Purpose:** Examine blood pressure, blood sugar, HbA1c, BMI, and lipid-profile measurements.

**Main Visuals**
- Average HbA1c
- Average LDL
- Average Systolic Blood Pressure
- Average Diastolic Blood Pressure
- Blood Pressure Levels by Heart Disease Status
- HbA1c & Fasting Blood Sugar
- HbA1c & BMI by Heart Disease Status
- Lipid Profile Breakdown

**Analytical Focus**

This page supports comparisons of blood pressure and blood sugar measurements between patient groups. It also provides a way to examine BMI and lipid-profile indicators, including LDL, HDL, and triglycerides.

![Medical Risks & Health Indicators](https://github.com/user-attachments/assets/a57f270e-2ff3-485e-88ad-9fb293b61b5a)

### 5. Lifestyle

**Purpose:** Explore lifestyle-related variables and compare their distributions across patients with and without heart disease.

**Main Visuals**
- Average Sleeping Hours
- Average BMI
- Average Diet Quality
- Average Stress Score
- Stress Score Comparison
- Weekly Physical Activity
- Patient Distribution by Smoking Habits
- Overall Heart Disease Prevalence

**Analytical Focus**

This page allows users to examine stress scores, physical activity, sleep duration, diet quality, and smoking status in relation to heart disease status.

The relationship between stress score and heart disease prevalence is worth examining in the displayed data. Any interpretation should be based on the actual values and chart configuration; an observed association does not establish causation.

![Lifestyle](https://github.com/user-attachments/assets/bf1aa0f9-0b46-458b-8d61-4d070a5d59bf)

## Dataset Overview

The dataset includes the following fields used for the analysis:

| Category | Fields |
|---|---|
| Demographics | `patient_id`, `age`, `sex` |
| Heart Disease Outcome | `has_heart_disease` |
| Cardiovascular Measurements | `resting_heart_rate`, `max_heart_rate_achieved`, `st_depression` |
| Blood Pressure | `resting_bp_systolic`, `resting_bp_diastolic` |
| Blood Markers | `cholesterol_total`, `hdl`, `ldl`, `triglycerides`, `fasting_blood_sugar`, `hba1c` |
| Body Measurement | `bmi` |
| Symptoms | `chest_pain_type`, `exercise_induced_angina` |
| Medical History | `family_history` |
| Lifestyle | `smoker_status`, `alcohol_units_per_week`, `exercise_minutes_per_week`, `sleep_hours`, `stress_score`, `diet_quality_score` |

Additional dataset fields may include wearable ownership and daily activity information.

## Interactive Features

- Interactive slicers and filters
- Cross-filtering between visuals
- Page-navigation buttons
- Help Tooltips explaining the analytical questions associated with visuals
- Dynamic visual updates based on filter selections

Available filters vary by page and may include age segmentation, gender, heart disease status, smoking status, stress score, alcohol consumption, and exercise minutes per week.

## Tools & Techniques

- Microsoft Power BI
- Exploratory Data Analysis (EDA)
- Data Visualization
- KPI Cards
- Bar Charts and Column Charts
- Scatter Plots
- Percentage-Stacked Charts
- Interactive Slicers
- Cross-Filtering
- Report Navigation
- Help Tooltips

## Key Findings & Interpretation

The dashboard supports the exploration of differences between patients with and without heart disease across medical indicators, cardiovascular measurements, and lifestyle characteristics.

The visualizations allow users to investigate patterns related to age, chest pain, exercise-induced angina, blood pressure, blood sugar, lipid-profile measurements, and lifestyle factors.

Specific findings should be interpreted using the displayed values and the current filter selections. These comparisons describe patterns in the dataset and do not establish causation or statistical significance.

## Limitations

- The analysis is descriptive and does not establish causal relationships.
- Findings depend on the quality, coverage, and representativeness of the dataset.
- Averages and percentages may hide differences within subgroups.
- KPI values and visual patterns may change when filters are applied.
- The dashboard is for educational and analytical purposes only and is not a medical diagnosis or clinical risk assessment.

## Author

**Habiba Ahmed**  
AI & Data Engineering | Data Analytics

GitHub: [Add GitHub Profile Link]  
LinkedIn: [Add LinkedIn Profile Link]
