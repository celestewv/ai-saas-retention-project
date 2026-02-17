# Customer Churn & Retention Transformation Case Study

## Overview
Data-driven churn segmentation and retention strategy case study using the Telco Customer Churn dataset. The goal is to identify high-risk segments and propose a future-state onboarding and feature adoption framework to improve retention.

## Key Findings (Current State / As-Is)
- Overall churn: **26.58%**
- Early lifecycle churn (0–12 months): **47.7%**
- Month-to-month churn: **42.7%**
- Customers without TechSupport churn: **41.6%** vs **15.2%** with TechSupport
- Estimated impact: reducing churn by 5pp preserves ~**352 customers** and **~$22.8k/month** in revenue (using avg MonthlyCharges)

## Recommendation (Future State / To-Be)
- Guided onboarding workflow for early lifecycle customers
- Automated feature activation nudges (TechSupport, OnlineSecurity)
- KPI tracking dashboard (activation, retention, feature adoption)
- Contract upgrade prompt after activation milestone

## Artifacts
- Notebook: `notebooks/01_churn_segmentation_case_study.ipynb`
- PRD: `docs/PRD_retention_onboarding.md`
- Experiment plan: `docs/experiment_plan.md`
