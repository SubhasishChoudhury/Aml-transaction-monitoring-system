# AML Alert Prioritization & Case Management System

## Project Overview

This project simulates an Anti-Money Laundering (AML) alert investigation workflow. Suspicious alerts generated from transaction monitoring systems are prioritized based on risk scores, converted into investigation cases, assigned to AML analysts, tracked through different investigation stages, and evaluated for Suspicious Activity Report (SAR) decisions.

## Business Problem

Financial institutions receive thousands of AML alerts daily. Investigating every alert with equal priority is inefficient and resource-intensive. AML teams need a structured process to prioritize alerts, assign investigators, track case progress, and identify cases requiring SAR consideration.

This project demonstrates a complete AML case management workflow that helps investigators focus on the highest-risk alerts.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Kaggle Notebook

## Features

### Alert Prioritization Engine

- Assigns priority levels based on AML risk scores.
- Categorizes alerts into:
  - Critical
  - High
  - Medium
  - Low

### Alert ID Generation

- Generates unique AML Alert IDs.
- Enables tracking of suspicious alerts.

### Case Management Workflow

- Converts alerts into investigation cases.
- Generates unique Case IDs.
- Tracks investigation lifecycle.

### Investigator Assignment

- Assigns AML analysts to cases.
- Simulates workload distribution across investigators.

### Case Status Tracking

Cases move through different stages:

- Open
- Under Review
- Escalated
- Closed

### SAR Decision Engine

Cases are categorized into:

- SAR Required
- SAR Review Needed
- No SAR Required

This helps prioritize regulatory reporting activities.

## Exploratory Data Analysis (EDA)

The project includes:

### EDA 1: Alert Distribution by Transaction Type

Analyzes which transaction types generate the highest number of alerts.

### EDA 2: AML Alert Risk Level Distribution

Analyzes alert distribution across risk levels.

### EDA 3: Alert Priority Distribution

Evaluates the volume of Critical, High, Medium, and Low priority alerts.

### EDA 4: Investigator Workload Analysis

Measures case allocation across AML investigators.

### EDA 5: Case Status Distribution

Tracks investigation progress through the case management lifecycle.

### EDA 6: SAR Decision Distribution

Analyzes the proportion of cases requiring SAR consideration.

### EDA 7: Critical Cases Requiring Investigation & SAR Review

Reviews the highest-priority AML cases.

## Key Results

| Metric | Value |
|----------|---------:|
| Total Alerts | 20,276 |
| Critical Alerts | 2,861 |
| High Priority Alerts | 5,787 |
| SAR Required Cases | 2,861 |
| SAR Review Cases | 5,787 |
| No SAR Required Cases | 11,628 |

## Project Workflow

Transaction Monitoring Alerts
↓
Risk Scoring
↓
Alert Prioritization
↓
Case Creation
↓
Investigator Assignment
↓
Case Status Tracking
↓
SAR Decision Engine

## Project Files

- AML Alert Prioritization & Case Management.ipynb
- AML_Case_Management_Final.csv
- EDA Visualizations
- Summary Metrics Dashboard

## Business Impact

This system helps AML operations teams:

- Prioritize high-risk alerts.
- Improve investigator efficiency.
- Monitor case progress.
- Support SAR decision-making.
- Generate management-ready AML metrics.

## Future Enhancements

- Machine Learning-based alert prioritization.
- Dynamic investigator workload balancing.
- Automated case escalation.
- Real-time AML dashboard integration.

## Author

**Subhasish Choudhury**
