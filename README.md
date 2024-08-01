# Quantzig Data Engineer Case Study

This project involves creating a logic module that performs data quality checks on an Excel dataset (`Data - DE.xlsx`) based on predefined rules (`Rules - DE.xlsx`) and sends a notification with consolidated data quality issues. Additionally, the module cleans the data according to predefined rules and saves the cleaned dataset.

## Table of Contents

- Introduction
- Requirements
- [Dataset](https://github.com/theNarendra25/Quantzig-Data-Engineer-Case-Study-/blob/main/Data%20-%20DE.xlsx)
- Steps :
  - Step 1: Import Required Libraries
  - Step 2: Load Dataset and Rules
  - Step 3: Perform Quality Checks
  - Step 4: Implement Issues Correction
  - Step 5: Save the Cleaned Dataset
  - Step 6: Send Notification with Consolidated Issues
- [Author](https://www.linkedin.com/in/narendra-kumar-meena-a5573420b/)
- License

## Introduction

This project ensures the quality of data in Excel files by performing various checks such as verifying sheet presence, column names, data types, and null values. It also includes data cleaning functionalities to ensure data consistency and sends a notification with the identified data quality issues.

## Requirements

- Python 3.x
- Pandas
- Openpyxl
- Smtplib

You can install the required libraries using:
```bash
pip install pandas openpyxl
