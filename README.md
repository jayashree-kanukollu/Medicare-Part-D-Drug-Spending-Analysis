# Medicare Part D Drug Spending Trend Analysis

## Project Overview
Analyzed Medicare Part D prescription drug spending trends across U.S. states and therapeutic categories using CMS data from 2017–2023. This analysis was developed as Use Case 1 of a collaborative healthcare analytics capstone project.

The objective was to identify geographic and disease-category spending trends, evaluate historical cost growth, and develop exploratory spending projections to support healthcare budgeting and resource planning.

## Tools and Technologies
- Python
- Pandas and NumPy
- Scikit-learn (Linear Regression)
- Jupyter Notebook
- Microsoft Excel

## Methodology
1. Prepared complete-case and imputed Medicare Part D datasets for trend analysis.
2. Aggregated prescription drug spending by state, disease category, and year.
3. Applied linear regression to estimate annual spending trends for 2017–2023.
4. Evaluated trend fit using R-squared and retained models meeting a 0.70 threshold.
5. Generated exploratory linear projections for 2024–2027 and a 5% cost-increase scenario.
6. Compared spending trend estimates between complete-case and imputed datasets.

## Key Findings
- Identified substantial differences in spending growth across geographic regions and therapeutic categories.
- Gastroenterology/Endocrinology and Oncology/Immunology showed some of the largest positive national spending trend slopes in the notebook results.
- California, Texas, New York, and Florida featured prominently in high-growth state-level spending trends.
- Compared complete-case and imputed results to examine how missing-data treatment influenced trend estimates.

## Limitations
The 2024–2027 estimates are exploratory linear extrapolations, not validated forecasts. The historical period includes only seven annual observations per state-category series. Results should not be interpreted as causal findings.

## Project Attribution
This repository highlights my contribution to Use Case 1 (Drug Spending Trend Analysis) within a collaborative academic capstone project.

## Data Source
Centers for Medicare & Medicaid Services (CMS), Medicare Part D Prescribers data, 2017–2023.
