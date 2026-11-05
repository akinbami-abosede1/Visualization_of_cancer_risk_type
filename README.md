# Interactive Analysis and Visualization of Risk Factors Across Different Cancer Types

# Project Overview

This project features an interactive **Power BI Dashboard** developed to explore, visualize, and compare demographic, lifestyle, dietary, genetic, health, environmental, and occupational risk factors across **2,000 patient observations**.

While conventional static reports can obscure important patterns due to the high number of variables involved, this dashboard provides a dynamic, user-driven platform for analysing cancer risk factors at both an aggregate level and across five distinct cancer types:

* Breast Cancer
* Colon Cancer
* Lung Cancer
* Prostate Cancer
* Skin Cancer

## Aim and Objectives

### Main Aim

To develop an interactive visual analytics platform for exploring multidimensional cancer risk profiles across different cancer types.

### Key Objectives

* Visualize demographic characteristics based on **age, age categories, and gender**.
* Examine the distribution of **individual cancer types** within the population.
* Evaluate behavioural risk indicators, including **smoking, alcohol consumption, physical activity, and obesity scores**.
* Assess dietary risk indicators, including **red meat, salted/processed foods, fruits and vegetables, and calcium intake**.
* Visualize genetic and health-related factors, including **family history, BRCA mutation, *****H. pylori***** infection, and BMI**.
* Examine environmental and occupational exposures, particularly **air pollution and occupational hazards**.
* Compare risk-factor patterns across different cancer types and risk classifications.

---

## Dataset Profile

The dataset contains **2,000 observations** covering demographic, lifestyle, dietary, genetic, health, environmental, and occupational variables.

### Gender Distribution

| Gender | Percentage |
| ------ | ---------: |
| Female |      51.1% |
| Male   |      48.9% |

The dataset is relatively balanced by gender, while the age distribution is concentrated among **middle-aged and older adults**.

### Cancer Type Distribution

| Cancer Type     |  Patients |
| --------------- | --------: |
| Breast Cancer   |       460 |
| Colon Cancer    |       418 |
| Lung Cancer     |       527 |
| Prostate Cancer |       305 |
| Skin Cancer     |       290 |
| **Total**       | **2,000** |

---

## Dashboard Architecture

The Power BI dashboard is organized into two primary analytical views.

### 1. General Cancer Risk Dashboard
<img width="991" height="567" alt="Cancer_risk_dashboard" src="https://github.com/user-attachments/assets/19a1e3fc-cd29-40b4-9a7d-dbd4e7ebe55f" />
Provides an aggregated overview of all **2,000 observations**, allowing users to examine overall patterns in:

* Demographics
* Cancer type distribution
* Lifestyle factors
* Dietary factors

* Genetic and health factors
* Environmental exposures
* Occupational hazards
* Overall cancer risk

### 2. Cancer-Specific Dashboards

Interactive filters and slicers allow users to isolate and examine individual cancer cohorts:

* **Breast Cancer** — 460 patients
* **Colon Cancer** — 418 patients
* **Lung Cancer** — 527 patients
* **Prostate Cancer** — 305 patients
* **Skin Cancer** — 290 patients

This filtering structure enables comparison of risk-factor patterns across cancer types and risk levels.

---

## Key Analytical Findings

###  Lung Cancer

Lung cancer showed a particularly strong pattern around smoking-related risk indicators. The high-risk cohort recorded a smoking-related score of **9.40**, alongside a high air-pollution exposure score of **9.30**.

### Breast Cancer

The high-risk breast cancer cohort was characterized by elevated **alcohol-use and obesity scores**, reaching **8.85** and **9.08**, respectively.

### Colon and Prostate Cancers

Colon and prostate cancer cohorts demonstrated notable dietary risk patterns. Red-meat consumption reached **8.83** among high-risk colon cancer observations and **7.33** among high-risk prostate cancer observations. Processed-food intake also showed elevated values within higher-risk groups.

### Skin Cancer

Skin cancer demonstrated a distinctive environmental and occupational exposure pattern. The occupational-hazard score reached **8.30** within the high-risk category.

### Fruit and Vegetable Intake

Across the cancer-specific dashboards, higher fruit and vegetable intake generally appeared more frequently among lower-risk cohorts. This represents a descriptive association within the dataset and should not be interpreted as evidence of a causal protective effect.

### Overall Pattern

Across the dashboards, higher-risk classifications generally coincided with higher scores for several lifestyle, dietary, and environmental exposure indicators. However, the strength and profile of these patterns varied by cancer type.

---

## Tech Stack and Tools

### Data Analytics and Visualization

* **Microsoft Power BI Desktop**
* Power Query for data preparation and transformation
* Interactive slicers and filters
* Data modelling and dashboard design

### Visualizations

The dashboard incorporates several visualization techniques, including:

* **Clustered horizontal bar charts** — Lifestyle and dietary risk scores
* **Donut charts** — Gender distribution
* **Column charts/histograms** — Age groups and risk-level distributions
* **Scatter plots** — BMI and overall cancer-risk relationships
* **Cards/KPIs** — Key population and risk metrics
* **Interactive slicers** — Cancer-type and risk-level filtering

---

## Future Improvements

Future versions of the project could extend the descriptive dashboard into a more comprehensive analytical and predictive system.

### Predictive Modelling

* Develop **logistic regression models** for risk classification.
* Evaluate machine-learning classifiers such as:

  * Random Forest
  * XGBoost
  * Support Vector Machines
  * K-Nearest Neighbours
* Compare model performance using appropriate evaluation metrics.
* Explore feature importance to identify variables contributing most strongly to model predictions.

###

---

## Disclaimer

This project is intended for **data analytics, visualization, and portfolio purposes**. The findings represent patterns observed within the available dataset and should not be interpreted as clinical diagnoses, medical recommendations, or evidence of causal relationships between specific risk factors and cancer.

---

## Project Focus

**Domain:** Data Analytics & Business Intelligence
**Platform:** Microsoft Power BI
**Dataset Size:** 2,000 observations
**Cancer Types:** 5
**Primary Focus:** Cancer risk-factor exploration, comparative analysis, and interactive visualization
