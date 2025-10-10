# Change Log

This file tracks all the changes made in the `djs-gdg-tasks` folder.

## 11 October 2025
- Added new datasets `df_dnf.csv` and `df_finish.csv` to the folder.
- Initialized a Git repository in the `djs-gdg-tasks` folder.
- Updated `EDA.ipynb` with the following changes:
  - Added exploratory data analysis for the `df_dnf.csv` dataset.
  - Visualized the distribution of `positionOrder` and `points` columns.


## 9 October 2025
- Shortened the log in the README.md file.
- Updated the README.md file to include details about Task 1.
- Reduced columns in the dataset `f1_dnf.csv` and created a new dataset `f1_dnf_reduced.csv` with the following changes:
  - **Dropped Columns**: `surname`, `forename`, `dob`, `name`, `location`, `country`, `lat`, `lng`, `alt`, `date`
  - **Added Column**: `full_name` (combination of `forename` and `surname`)

## 8 October 2025
- Added functionality to extract and count Lal Chandan Trees in a specified zone in `task_1.ipynb`.