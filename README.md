README

Project Overview
This project analyzes COVID-19 case, testing, and mortality data to uncover trends, identify inconsistencies, and support decision-making through visual dashboards and data insights. The dataset includes state-wise case counts, statewise testing details, and a deaths table created from scratch. Derived measures include Total Positive, Total Negative, Daily Positivity, and Positivity Rate. The goal is to clean the data, perform exploratory analysis, create visualizations, and prepare the dataset for further predictive or analytical uses.

Data Sources

1. Statewise case data containing daily counts of positive, negative, and total tests.
2. Deaths table containing mortality counts, confirmed cases counts, and associated state identifiers; used for mortality trend analysis and cross-validation with case and testing data.
3. Calculated measures: Total Positive, Total Negative, Daily Positivity, and Positivity Rate.

Key Tasks Performed

1. Data cleaning: handled missing records, corrected inconsistent dates, standardized state names, reconciled duplicate and partial records, and validated the manually created deaths table.
2. Data integration: merged the deaths table with case and testing datasets to enable combined analyses of cases, testing intensity, and mortality.
3. Data validation: cross-verified figures across tables to identify gaps, mismatches, and likely data-entry errors.
4. Exploratory analysis: examined trends, distributions, and anomalies in positivity, testing behaviour, and mortality.
5. Visual dashboard: built a Power BI dashboard using maps, tables, and calculated measures to present insights clearly; included mortality visualizations sourced from the deaths table.
6. Export & preparation: created aggregated tables for Total Positive, Total Negative, Daily Positivity, Positivity Rate, and mortality summaries for external use such as Kaggle uploads.

Notable Challenges
The datasets contained missing rows, inconsistent date formats, duplicated or partial records, and incomplete state information. The manually created deaths table required validation and reconciliation against case and testing data to ensure consistency and reliability.

Project Outcomes
The final dashboard provides an interpretable view of COVID-19 trends across states, including testing intensity, positivity fluctuations, and mortality trends derived from the deaths table. Key insights include correlations between testing volume and detected cases, temporal shifts in positivity, and mortality patterns. The cleaned dataset and measures can now be used for further analysis, predictive modeling, reporting, or public dashboards.

Files Included

* Cleaned datasets (cases, testing details, deaths table)
* Aggregated measure tables (Total Positive, Total Negative, Daily Positivity, Positivity Rate, Mortality summary)
* Power BI dashboard file and supporting data export (CSV/Excel)

Usage
Users may load the cleaned datasets and aggregated tables into analysis tools or BI platforms, adapt visualizations in the Power BI dashboard, or use the prepared data for modeling and reporting.

Contact
For questions, corrections to the deaths table, or collaboration, please reach out through the repository’s issue tracker.
