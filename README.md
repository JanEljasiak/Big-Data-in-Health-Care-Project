# Big Data in Health Care Project

**Authors:** Jan Robert Eljasiak
**Year:** 2025  

---

## Project Overview

This project investigates the outcomes of patients with **hepatocellular carcinoma (HCC)** after primary tumor resection, focusing on:

- Tumor recurrence  
- Mortality without recurrence  
- Composite outcomes (recurrence or death)  

The analysis uses a dataset containing patient demographics, clinical characteristics, treatment information, and follow-up data to explore patterns of recurrence and evaluate prognostic factors.

---

## Objectives

1. **Descriptive Analysis**  
   - Summarize patient characteristics and clinical variables  
   - Visualize distributions of numerical and categorical data  

2. **Competing Risks Analysis**  
   - Assess the impact of first recurrence treatment on second recurrence and death without recurrence  

3. **Survival Analysis (Cox Models)**  
   - Identify risk factors associated with adverse outcomes  
   - Develop predictive models for time-to-event outcomes  

4. **Model Evaluation**  
   - Evaluate predictive performance (calibration, discrimination, net benefit)  
   - Apply models for individual risk prediction  

---

## Methods

- **Data Processing:** R programming with tidy data principles  
- **Descriptive Statistics:** Numerical summaries, frequency tables, histograms, and boxplots  
- **Competing Risks:** Cumulative incidence functions and Gray’s test  
- **Survival Analysis:** Univariate and multivariable Cox proportional hazards models  
- **Model Evaluation:** Calibration plots, ROC curves, AUC, and decision curve analysis  

---

## Tools and Packages

- **R** with the following packages: `survival`, `cmprsk`, `dcurves`, `ggplot2`, `tidyr`, `psych`, `pROC`, `summarytools`  

---

## Purpose

The goal of this project is to **understand prognostic factors for HCC recurrence and mortality** and to develop predictive models to support **clinical decision-making and patient risk stratification**.
