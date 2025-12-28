cat > README.md << 'EOF'
# Bellabeat Smart Device Usage Analysis (Fitbit Dataset)

## Overview
This repository contains a portfolio case study analyzing smart device usage data (Fitbit) to identify behavior trends and translate them into marketing recommendations for Bellabeat, a wellness technology company.

## Business Task
Analyze smart device usage data to:
1. Identify trends in smart device usage
2. Explain how these trends could apply to Bellabeat customers
3. Provide high-level recommendations to inform Bellabeat’s marketing strategy

## Dataset
- **Source:** Kaggle – FitBit Fitness Tracker Data (arashnic/fitbit)
- **License:** CC0 (Public Domain)
- **Access method:** Downloaded programmatically via `kagglehub` (raw data is not committed to this repository)

## Tech Stack
- Python
- Pandas
- Jupyter Notebooks
- GitHub / Codespaces

## Repository Structure
notebooks/
01_load_and_clean.ipynb
02_usage_analysis.ipynb
03_visuals_for_report.ipynb
04_recommendations_and_next_steps.ipynb
data_raw/ # ignored by git (local only)
data_cleaned/
reports/figures/ # exported visuals
README.md
requirements.txt
.gitignore

## How to Run (Codespaces)
1. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt
2. Open notebooks in order:

notebooks/01_load_and_clean.ipynb

notebooks/02_usage_analysis.ipynb

notebooks/03_visuals_for_report.ipynb

notebooks/04_recommendations_and_next_steps.ipynb