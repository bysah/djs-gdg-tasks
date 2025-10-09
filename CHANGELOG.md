# Change Log

This file tracks all the changes made in the `djs-gdg-tasks` folder.

## 9 October 2025
- Shortened the log in the README.md file.
- Updated the README.md file to include details about Task 1.
- Reduced columns in the dataset `f1_dnf.csv` and created a new dataset `f1_dnf_reduced.csv` with the following changes:
  - **Dropped Columns**: `surname`, `forename`, `dob`, `name`, `location`, `country`, `lat`, `lng`, `alt`, `date`
  - **Added Column**: `full_name` (combination of `forename` and `surname`)
                      `location_country`(combination of `location` and `country`)

## 8 October 2025
- Added functionality to extract and count Lal Chandan Trees in a specified zone in `task_1.ipynb`.