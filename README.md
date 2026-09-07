# Motor Insurance Claims Analysis

A Python-based analysis of an anonymized motor insurance portfolio, examining claim occurrence, claim costs, loss ratios, and risk patterns across vehicle types and geographic areas.

## Overview

This project analyzes 105,555 policy-periods from a motor insurance portfolio. The analysis focuses on:

- Overall claim occurrence, claim cost, and loss ratio
- Claim cost concentration
- Differences across vehicle types
- Rural vs. urban claim patterns
- Vehicle type and area segmentation
- Statistical association between area and claim occurrence

## Key Findings

- 18.61% of policy-periods recorded at least one claim.
- The overall loss ratio was 48.61%.
- The highest-loss 10% of claim-bearing policy-periods accounted for 57.33% of total claim costs.
- Vans had the highest loss ratio at 50.67%, while motorbikes had the lowest at 25.27%.
- Urban loss ratios were higher than rural loss ratios for passenger cars and vans.
- Area was statistically associated with claim occurrence, but the association was very weak (Cramer's V = 0.029).

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

## Dataset

This project uses the *Dataset of an actual motor vehicle insurance portfolio*, published by Josep Lledó and Jose M. Pavía and released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

The dataset contains anonymized motor insurance data from a Spanish non-life insurance company. The raw dataset is not included in this repository.

Source: https://doi.org/10.17632/5cxyb5fp4f.2

## Project Structure

```text
insurance-claims-analysis/
├── README.md
└── insurance_claims_analysis.ipynb
```