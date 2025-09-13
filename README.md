# Duplicate Rows Analysis

This repository contains a Jupyter Notebook (`duplicates_analysis.ipynb`) that demonstrates how to **detect duplicate rows** in a dataset using **Pandas**.  

## Dataset
The data used is from a public Kaggle dataset:  
I have included the dataset csv as ncr_ride_bookings.csv

## Objective
The notebook focuses on:
- Identifying whether certain columns (e.g., `Booking ID`) contain duplicates.  
- Extracting duplicate rows for inspection.  
- Summarizing the results to highlight potential data quality issues.  

## Why This Matters
Duplicate values can seriously affect analysis and model accuracy.  
This notebook shows how to **detect duplicates** — whether to drop them or keep them depends on the dataset context.  

## How to Run
1. Clone this repo.  
2. Open the notebook in JupyterLab / Jupyter Notebook.  
3. Run all cells step by step.  

## Requirements
- Python 3.8+  
- Pandas  

Install dependencies with:
```bash
pip install pandas
