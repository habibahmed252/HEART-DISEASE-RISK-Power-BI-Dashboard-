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
- **Average LDL:** What is the average LDL level in the selected population?
- **Average Systolic Blood Pressure:** What is the average systolic blood pressure?
- **Average Diastolic Blood Pressure:** What is the average diastolic blood pressure?
- **Blood Pressure Levels:** How do systolic and diastolic measurements compare by heart disease status?
- **HbA1c & Fasting Blood Sugar:** How do these blood sugar indicators compare between the two groups?
- **HbA1c & BMI by Heart Disease Status:** How do these measurements vary by outcome?
- **Lipid Profile Breakdown:** How do LDL, HDL, and triglycerides compare between the groups?

**Key Insights**

- Comparing systolic and diastolic blood pressure by outcome can show whether the groups have different average profiles.
- HbA1c and fasting blood sugar describe related but different aspects of blood-glucose status; they should not be treated as interchangeable measurements.
- LDL, HDL, and triglycerides should be reviewed together for a broader lipid-profile comparison.
- BMI may vary across the outcome groups, but group averages do not describe every patient's individual risk.
- Slicers can be used to check whether observed patterns remain similar across age segments, sex, smoking status, stress score, and heart disease status.

### 5. Lifestyle

**Purpose**

This page explores how lifestyle-related variables are distributed and how they compare between patients with and without heart disease.

**Main Visuals & Questions**

- **Average Sleeping Hours:** What is the average reported sleep duration?
- **Average BMI:** What is the average BMI in the selected population?
- **Average Diet Quality:** What is the average diet-quality score?
- **Average Stress Score:** What is the average stress score?
- **Stress Score Comparison:** How does average stress score differ between the two outcome groups?
- **Weekly Physical Activity:** How do weekly exercise minutes compare between the groups?
- **Patient Distribution by Smoking Habits:** How are patients distributed across smoking categories?
- **Overall Heart Disease Prevalence:** How many cases and non-cases are represented in the selected population?

**Key Insights**

- Higher stress scores appear associated with higher observed heart disease prevalence in this dataset. This is an association, not proof of causation.
- Comparing weekly exercise minutes can reveal differences in reported activity between the groups.
- Sleep duration and diet-quality scores add context to the lifestyle profile of the selected population.
- Smoking comparisons should be interpreted with the size and composition of each smoking category in mind.
- Filters for stress score, exercise minutes, alcohol consumption, age segment, sex, and smoking status allow more focused comparisons.

---

## Interactivity & User Experience

The report includes interactive filters such as:

- Age Segmentation
- Gender
- Heart Disease Status
- Smoking Status
- Stress Score
- Alcohol Units per Week
- Exercise Minutes per Week

Available filters vary by page. Selecting a filter updates the relevant visuals so users can compare specific segments of the patient population.

The report also includes page-navigation buttons and Help Tooltips that explain the analytical question associated with selected visuals.

## Key Findings — Summary

- The dashboard enables comparison of medical indicators and lifestyle characteristics by heart disease status.
- Stress score is a pattern worth investigating because higher scores appear associated with higher heart disease prevalence in this dataset.
- Age-group, chest-pain, exercise-induced-angina, blood pressure, blood sugar, and lipid-profile comparisons provide additional context for understanding differences between the groups.
- Interactive filters make it possible to explore whether these patterns vary across demographic and lifestyle subgroups.

These findings should be checked against the final dashboard values before publication. The relationships described are not proof of causation, and statistical significance should not be claimed unless suitable statistical tests have been performed.

## Limitations

- The dashboard presents descriptive comparisons and associations; it does not establish causality.
- Results depend on the dataset's coverage, quality, definitions, and representativeness.
- Averages and percentages may hide variation within subgroups.
- Filter selections change the population being summarized, so KPI values should always be read in the context of the active filters.
- This report is for educational and analytical purposes only and is not a medical diagnosis or clinical risk assessment.

## Future Improvements

- Add a clear data-source citation and data dictionary.
- Document data cleaning and transformation steps.
- Include verified record counts and final KPI values.
- Add statistical tests or confidence intervals where appropriate.
- Improve accessibility with consistent labels, readable contrast, and descriptive alt text for screenshots.
- Validate every Help Tooltip question against the visual it describes.
- Add a short guided walkthrough explaining the most important findings.

## Project Structure

```text
Heart-Disease-Risk/
├── README.md
├── images/
│   ├── home.png
│   ├── overview.png
│   ├── heart-indicators.png
│   ├── medical-risks.png
│   └── lifestyle.png
├── dashboard/
│   └── heart-disease-risk.pbix
└── demo/
    └── youtube-demo-link.txt
```

Adjust the folder structure to match the files you choose to publish.

## Author

**Habiba Ahmed**  
AI & Data Engineering | Data Analytics

- GitHub: [Add your GitHub profile link]
- LinkedIn: [Add your LinkedIn profile link]
