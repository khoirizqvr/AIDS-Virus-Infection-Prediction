# Predicting AIDS Virus Infection Using Patient Health Statistics

This project focuses on predicting AIDS infection status using patient health statistics and categorical information. The dataset, sourced from Kaggle, contains various features such as patient demographics, medical history, treatment history, and lab test results. The target variable is `infected`, which indicates whether the patient has been diagnosed with AIDS.

---

## Project Overview

### Steps:
1. **Data Collecting**
2. **Data Analysis**
3. **Data Validation**
4. **Object Determining**
5. **Data Cleaning**
6. **Feature Engineering**
7. **Label Definition**
8. **Model Building**
9. **Model Comparison**

## Dataset Description
The dataset contains health statistics and medical treatment details of patients. Each row represents a unique patient, and the target variable `infected` indicates their AIDS infection status.

**Target Variable:**
- `infected`: 0 (No) or 1 (Yes)

### Features
1. `time`: Time to failure or end of observation.
2. `trt`: Treatment indicator (0: ZDV only, 1: ZDV + ddI, 2: ZDV + Zal, 3: ddI only).
3. `age`: Age (in years) at observation start.
4. `wtkg`: Weight (in kg) at observation start.
5. `hemo`: Hemophilia status (0: No, 1: Yes).
6. `homo`: Homosexual activity (0: No, 1: Yes).
7. `drugs`: History of intravenous drug use (0: No, 1: Yes).
8. `karnof`: Karnofsky score (scale of 0-100).
9. `oprior`: Non-ZDV antiretroviral therapy before 175 days (0: No, 1: Yes).
10. `z30`: ZDV usage in the last 30 days before 175 days (0: No, 1: Yes).
11. `preanti`: Days of antiretroviral therapy before 175 days.
12. `race`: Race (0: White, 1: Non-white).
13. `gender`: Gender (0: Female, 1: Male).
14. `str2`: Antiretroviral history (0: New, 1: Experienced).
15. `strat`: Antiretroviral stratification (1: Naive, 2: 1-52 weeks, 3: >52 weeks).
16. `symptom`: Symptom indicator (0: Asymptomatic, 1: Symptomatic).
17. `treat`: Treatment indicator (0: ZDV only, 1: Other).
18. `offtrt`: Treatment discontinuation before 96 weeks (0: No, 1: Yes).
19. `cd40`: Initial CD4 count.
20. `cd420`: CD4 count at 20 weeks.
21. `cd80`: Initial CD8 count.
22. `cd820`: CD8 count at 20 weeks.

## Models Used
1. Naive Bayes
2. Random Forest Classifier
3. Support Vector Machine (SVM)
4. Logistic Regression
5. Decision Tree

## Results
From the dataset, a comparison of model accuracies revealed that Random Forest achieved the highest accuracy at 94%, followed by K-Nearest Neighbors (KNN) with 90% and Decision Tree with 89%. Support Vector Machine (SVM) reached 86%, Logistic Regression 84%, and Naive Bayes 83%.

