# Workplace Insight Report

**Author:** Niranjan  
**Date:** 26 April 2025  

---

## Project Background

This project explores the dynamics of workplace conditions and employee behavior, focusing on job satisfaction, stress levels, training hours, overtime, and more. As a Data Analyst, the goal was to uncover key patterns that could inform workforce management strategies, enhance employee well-being, and guide organizational development.

Insights and recommendations are provided on the following key areas:

- **Experience and Training Correlation**
- **Continuous Variable Interactions**
- **Overtime Impact on Work-Life Factors**
- **Stress, Sleep, and Job Satisfaction Dynamics**

Python notebooks used to inspect, clean, and analyze the data can be found in the repository.  
Visualizations from the analysis are included below to support the findings.

---

## Data Structure & Key Fields

The primary data fields include:

- **Age**  
- **Experience**  
- **Sleep_Hours**  
- **Stress**  
- **Job_Satisfaction**  
- **Overtime**  
- **Training_Hr_Yr**  
- **Work_Env_Rating**  
- **Work_Load**  
- **Physical_Activity_Hr**  
- **Commute_Distance**  

---

## Executive Summary

### Overview of Findings

- There is a clear upward trend in training hours with experience across all job levels.
- Age and experience show strong positive correlation with training hours.
- Work environment quality correlates positively with job satisfaction, while stress and workload are negatively associated.
- Overtime tends to be more frequent in younger, less experienced employees, potentially impacting sleep and satisfaction.

---

## Visual Insights

### 1. **Experience vs Training Hours by Job Level**

A clear positive trend is observed where training hours increase with experience across all job levels. Higher roles like "Lead" and "Senior" spend more time annually on training compared to "Intern/Fresher" or "Junior" roles.

![Experience_vs_Training_Hours_by_Job_Level](images/Experience_vs_Training_Hours_by_Job_Level.png)

---

### 2. **Correlation Heatmap – Continuous Variables**

- Strong positive correlation between `Age`, `Experience`, and `Training_Hr_Yr`.
- `Job_Satisfaction` shows positive correlation with `Work_Env_Rating` and `Sleep_Hours`, and negative correlation with `Stress` and `Work_Load`.

![Correlation_Heatmap](images/Correlation_Heatmap_Continuous.png)

---

### 3. **Overtime Distribution by Key Variables**

This pairplot provides a multivariate look at how variables like `Age`, `Experience`, `Sleep_Hours`, `Stress`, and `Job_Satisfaction` differ for employees working overtime vs those who don’t.

![Overtime_Distribution_Pairplot](images/Overtime_Distribution_Pairplot.png)

---

## Recommendations

- Encourage structured training across all job levels to align with career growth and role responsibility.
- Monitor and manage overtime, especially for junior staff, to reduce stress and burnout risk.
- Foster better work environments to directly improve job satisfaction and mental well-being.
- Invest in programs that encourage better sleep and reduced commute time, contributing to overall employee productivity.

---

## Assumptions and Notes

- All correlations are based on Pearson coefficients and do not imply causation.
- Overtime is treated as a binary variable; more granular time data could improve resolution.
- Missing data points were excluded listwise for correlation and visual plots.

---

## 📬 Contact

For queries or collaborations:
- **Email**: [niranjan991100@gmail.com]  
- **LinkedIn**: [Niranjan's Profile](https://www.linkedin.com/in/niranjan-k-a83517229/)
