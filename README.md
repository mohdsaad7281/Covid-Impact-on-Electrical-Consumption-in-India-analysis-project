# Covid-Impact-on-Electrical-Consumption-in-India-analysis-project
Analyzed 2 years of state-wise electrical consumption data across 29 Indian states using MySQL, Excel and Power BI. Identified COVID-19 lockdown caused 59% drop in 2020, Maharashtra as top consuming state and July 2019 as peak month. Includes 7 SQL queries, Excel dashboard and interactive Power BI report.
# India Electrical Consumption Analysis 2019-2020

## Project Overview
Analysis of state-wise electrical consumption data across all Indian states 
from January 2019 to December 2020, uncovering consumption patterns, 
peak demand periods, and the impact of COVID-19 lockdown on electricity 
demand across India.

## Tools Used
- **MySQL** — Data storage and querying
- **Excel** — Data cleaning, transformation and dashboard
- **Power BI** — Interactive dashboard and visualization
- **Power Query** — Data transformation (wide to long format)

## Dataset
- **Source:** Kaggle
- **Period:** January 2019 to December 2020
- **Coverage:** 29 Indian States and Union Territories
- **Total Records:** 16,599 rows after transformation
- **Columns:** Date, State, Consumption (MU)

## Data Transformation
- Original dataset was in wide format with each state as a separate column
- Converted to long format using Excel Power Query
- Cleaned and standardized date format to YYYY-MM-DD
- Loaded into MySQL for querying and analysis

## Key Findings
- **Maharashtra** is the highest consuming state with 217,079 MU total
- **July 2019** recorded peak consumption of 118,600 MU
- COVID-19 lockdown caused a **59% drop** in electricity consumption in 2020
- Consumption dropped significantly during lockdown months April-June 2020
- Smaller states like Sikkim, Mizoram and Arunachal Pradesh had lowest consumption

## Files in This Repository
| `consumptionraw.xlsx` | Original Kaggle dataset |
| `consumptionfinal.csv` | Cleaned long format dataset |
| `queries.sql` | All 7 MySQL queries |
| `allsheetsdashboard.xlsx` | Excel dashboard and all different tables from sql queries |
| `India_Electrical_Analysis.pptx` | Project ppt |
| `electricalconsumptiondashboard.pbix` | Power BI dashboard |

## Author
MOHD SAAD
LinkedIn:www.linkedin.com/in/mohd-saad-5b052429b
