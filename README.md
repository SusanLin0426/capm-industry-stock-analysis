# CAPM Industry Stock Analysis

This repository contains the project analyzing the Capital Asset Pricing Model (CAPM) across multiple Taiwanese industries. The project estimates systematic risk (β) and abnormal return (α) for each industry and visualizes them with scatter plots.

---

## Project Structure
- `term_project_code.py` : Python script for data cleaning, regression, and CAPM analysis.
- `term_project_report.pdf` : User guide with detailed methodology and instructions.

---

## Research Overview

### Objectives
1. Collect industry and market return data from OTC/TSE sources.
2. Convert, clean, and preprocess raw Excel files into usable CSVs.
3. Estimate α (excess return) and β (systematic risk) for each industry.
4. Visualize industry-level CAPM results in scatter plots.
5. Provide case studies (e.g., biotech, shipping) linking CAPM estimates to real market performance.

### Methodology
- **Input:**  
  - Market return (Rm)  
  - Industry return (Ri) across 19 industries
- **Model:**  
  Ri = α + β * Rm
- **Output:**  
  - List of α and β coefficients per industry  
  - Scatter plot (X = β, Y = α) with industry labels  

---

## Environment & Dependencies
- Python 3.9+
- Required packages:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`
  - `openpyxl`
