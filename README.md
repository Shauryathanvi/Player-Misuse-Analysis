# Player Misuse Analysis (2021–2022 Football Stats)

This project explores **player role and position misuse** using 2021–2022 football player performance data.  
The analysis focuses on identifying where players may be underused or used outside their strongest profile, based on performance metrics and position context.

## Dataset origin

The original dataset used for this work comes from Kaggle:

- **2021-2022 Football Player Stats**: https://www.kaggle.com/datasets/vivovinco/20212022-football-player-stats

A copy of the original source file is included in this repository as:

- `2021-2022 Football Player Stats_Kaggle.csv`

## Updated dataset and simplification

For the purpose of this project, an updated Excel version was created:

- `2021-2022 Football Player Stats_updated.xlsx`

In this updated file, **some columns from the original dataset were intentionally removed** to keep the analysis focused on the project’s core goal (player misuse analysis) and to simplify data handling.

In short:
- The Kaggle file is the full original source.
- The updated Excel file is a streamlined version with selected features for easier and more targeted analysis.

## Repository contents

- `Position_misuse.ipynb` — Main notebook with data preparation and analysis workflow.
- `2021-2022 Football Player Stats_Kaggle.csv` — Original dataset snapshot from Kaggle.
- `2021-2022 Football Player Stats_updated.xlsx` — Simplified working dataset used in analysis.
- `2021-2022_PlayerMisuse_Analysis.xlsx` — Output/report workbook for project results.

## Project objective

The key objective is to provide a data-driven way to:

1. Define **position-specific KPIs** to get each player's Attacking, Midfielding and Defending scores
2. Single-out a player if their **dominating positional KPI score** is different from their proposed position in the original dataset
3. Helps in finding out if a player was "**misused"** positional-wise. 

## How to use

1. Open `Position_misuse.ipynb` in Jupyter Notebook/JupyterLab.
2. Ensure the dataset files are in the repository root (current structure).
3. Run notebook cells in order to reproduce analysis and outputs.

