# Labor Market Analytics — Job Satisfaction & Remuneration

## Overview
This paper investigates the relationship between employer-provided services 
and bonuses and employee job satisfaction in Nepal, using logistic regression 
and marginal effects analysis on nationally representative survey data.

## Dataset
Nepal Labour Force Survey (NLFS) 2017–2018, Third Round
Collected by the Central Bureau of Statistics (CBS)
78,496 raw observations | 16,032 observations used in final models

## Objectives
Determine whether cash remuneration and non-monetary benefits such as 
transportation and uniform facilities have a significant relationship with 
job satisfaction among Nepalese workers.

## Methodology
- Binary logistic regression (dependent variable: wanting to change current job)
- Marginal effects analysis to quantify probability changes
- Clustered standard errors using primary sampling unit (PSU)
- Two model specifications with different control variable combinations
- Control variables: working age group (15–64), agriculture sector, 
  education level, employment status

## Key Results
- Transportation facility reduced the probability of wanting to change jobs 
  by 7.99–8.12 percentage points (positively significant to job satisfaction)
- Uniform facility reduced the probability of wanting to change jobs 
  by 24.4–24.6 percentage points (strongest positive effect on job satisfaction)
- Cash remuneration showed a negative relationship with job satisfaction — 
  workers receiving cash were more likely to want to change jobs, consistent 
  with Herzberg's Two-Factor Theory (hygiene factors do not drive satisfaction)
- Residence and food/beverage facilities showed no significant relationship 
  with job satisfaction

## Key Insights
- Non-monetary benefits (transportation, uniform) are stronger drivers of 
  job satisfaction than cash remuneration alone
- Findings align with Herzberg's Two-Factor Theory — extrinsic/hygiene factors 
  prevent dissatisfaction but do not actively drive satisfaction
- Policy recommendations include subsidising transportation and uniform 
  facilities to improve workforce retention in Nepal

## Tools
STATA | R | Logistic Regression | Marginal Effects Analysis

## Disclaimer
Developed as an undergraduate research paper at Kathmandu University School 
of Arts (Bachelor in Economics, 2023). Raw dataset not included due to 
file size. Data sourced from Nepal's Central Bureau of Statistics.
