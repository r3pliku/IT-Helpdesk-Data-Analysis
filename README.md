# IT Help Desk Data Analysis

## Overview
Cleaned and analyzed a 50,000 row IT Help Desk 
dataset sourced from Kaggle using Google Sheets.

## Tools Used
- Google Sheets

## Data Cleaning Steps
- Split encoded columns into Rank and Label
- Flagged unassigned priority tickets
- Flagged same day resolved tickets
- Standardized column headers to snake_case
- Documented all changes in a Cleaning Log
- Completed full sanity check

## Key Findings
- 75% of tickets are Requests vs 25% Issues
- Systems department generates the most tickets
- 90% of tickets are Normal severity
- Regular employees submit the most tickets at 41%
- Requests take twice as long to resolve as Issues
  at 7.9 days vs 3.7 days

## Files
- IT_Help_Desk_Raw_Data.xlsx — original Kaggle dataset
- IT_Help_Desk_Cleaned_Data.xlsx — cleaned version
- IT_Help_Desk_Analysis.xlsx — pivot tables and charts
