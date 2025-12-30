# Multi-Source Data Quality Scorecard

## Overview
This project builds a comprehensive data quality scorecard by analyzing and comparing data quality across multiple sources, including a CSV file and a MySQL database.

## Objectives
- Assess data quality across multiple data sources
- Identify missing values and duplicate records
- Generate a consolidated quality scorecard
- Present results in an Excel report with visual indicators

## Data Sources
- CSV file
- MySQL database (simulated profiling used due to local environment constraints)

## Quality Metrics
- Completeness: Percentage of non-null values
- Accuracy: Duplicate record checks
- Consistency: Rule-based validation
- Overall Score: Average of all metrics

## Tools & Technologies
- Python
- Pandas
- SQLAlchemy
- MySQL
- Microsoft Excel

## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Run the script:
   python scripts/scorecard_generator.py
3. Open the Excel file from the output folder.

## Output
An Excel-based data quality scorecard comparing CSV and MySQL data sources.

## Notes
MySQL profiling was demonstrated using simulated metrics due to local environment constraints, while maintaining full end-to-end data quality scoring logic.

## Author
Jaya Kumari
