# Diabetes Patient Data Cleaning

## Project Overview
Cleaned a real-world medical dataset of 768 diabetes patients 
using Python, Pandas, and NumPy to prepare it for analysis.

## Problem Statement
Raw medical data contained missing values disguised as zeros — 
a common issue in healthcare datasets that leads to inaccurate analysis.

## What I Did
- Identified 652 missing values across 5 medical columns
- Replaced invalid zeros with statistically appropriate median values
- Removed duplicate patient records
- Exported a clean, analysis-ready dataset

## Key Findings
- Insulin data was missing for 48.7% of patients
- SkinThickness data was missing for 29.6% of patients
- BloodPressure had 35 invalid zero entries

## Tools Used
- Python 3.14
- Pandas
- NumPy
- Jupyter Notebook

## Dataset
Pima Indians Diabetes Database — UCI Machine Learning Repository
768 patient records, 9 medical features
