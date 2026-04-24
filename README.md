# Diabetes Patient Data Cleaning

## Project Overview
Cleaned a real-world medical dataset of **768 diabetes patients** using Python, Pandas, 
and NumPy to prepare it for machine learning and analysis.

## Problem Statement
Raw medical data contained **missing values disguised as zeros** — a common issue in 
healthcare datasets that leads to inaccurate analysis if not handled properly.

## Missing Values Visualization

![Missing Values Chart](missing_values_chart.png)

## Before vs After Cleaning

| Column | Missing (zeros) | % Missing | Action Taken |
|--------|----------------|-----------|--------------|
| Insulin | 374 | 48.7% | Median imputation |
| SkinThickness | 227 | 29.6% | Median imputation |
| BloodPressure | 35 | 4.5% | Median imputation |
| BMI | 11 | 1.4% | Median imputation |
| Glucose | 5 | 0.6% | Median imputation |
| **Total** | **652** | — | — |

## What I Did
- Identified **652 missing values** across 5 medical columns disguised as zeros
- Applied **median imputation** to preserve data distribution
- Removed duplicate patient records
- Exported clean, analysis-ready dataset (`diabetes_cleaned.csv`)

## Key Findings
- Insulin data missing in **48.7%** of patients — highest gap
- SkinThickness missing in **29.6%** of patients
- Total **652 invalid zero entries** found across 5 columns
- Median imputation chosen over mean to avoid outlier influence

## Tools Used
| Tool | Purpose |
|------|---------|
| Python 3 | Core programming |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Visualization |
| Jupyter Notebook | Development environment |

## Dataset
**Pima Indians Diabetes Database** — UCI Machine Learning Repository  
768 patient records | 9 medical features

## How to Run
1. Clone this repo
2. Install dependencies: `pip install pandas numpy matplotlib jupyter`
3. Open `diabetes_cleaning.ipynb` in Jupyter
4. Run all cells
