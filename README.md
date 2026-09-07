# Tennis Shot Quality & Tactical Pattern Analysis

MSc Data Science project analysing professional tennis shot quality and
tactical patterns using shot-by-shot notation data.

## Data

Source: The Tennis Abstract Match Charting Project by Jeff Sackmann
https://github.com/JeffSackmann/tennis_MatchChartingProject
Licensed CC BY-NC-SA 4.0. Raw data is NOT included in this repository.

To reproduce, download the following files into `data/raw/`:

- charting-m-points-2010s.csv
- charting-m-points-2020s.csv
- charting-w-points-2010s.csv
- charting-w-points-2020s.csv
- charting-m-matches.csv
- charting-w-matches.csv

Scope: 2010-present, men's and women's matches combined with a gender flag.

## Notebooks

- 01_data_loading.ipynb - loading, merging, cleaning
- 02_notation_parsing.ipynb - parsing shot notation into point- and shot-level tables
- 03_eda.ipynb - exploratory analysis
- 04_feature_engineering.ipynb - target and feature construction
- 05_modeling.ipynb - Logistic Regression, Random Forest, XGBoost
- 06_interpretation_shap.ipynb - SHAP and feature importance

## Setup

pip install -r requirements.txt
