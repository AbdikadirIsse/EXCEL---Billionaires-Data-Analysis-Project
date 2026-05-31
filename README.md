# Billionaires-Data-Analysis-Project
A full end-to-end data analysis project using a real-world dataset of the richest people in the world, covering data cleaning, analysis, and visualization in Excel.

## Dataset used
- <a href="https://github.com/AbdikadirIsse/Billionaires-Data-Analysis-Project/blob/main/Raw%20Uncleaned%20Billionaires%20Dataset.xlsx">Dataset</a>

## 1. Data Cleaning
- Created a backup copy of the raw data before making any changes
- Removed 6 duplicate rows using the Remove Duplicates tool
- Replaced abbreviated gender values (M → Male, F → Female) using Find & Replace
•	Created a new Age column by combining birth year, month, and day into a full birth date using the DATE function, then calculating age using YEARFRAC
•	Cleaned the Country GDP column by removing commas and dollar signs that were stored as text, then reformatted the column as a number with thousand separators

## 2. Data Analysis
### Descriptive Statistics
•	Used the built-in Data Analysis ToolPak to generate descriptive statistics for all numeric columns
•	Key findings: average net worth was ~$14.8B, maximum was $211B, total of 475 billionaires on the list, and the average age was 68
### Pivot Tables
•	Built a pivot table to identify the Top 10 richest individuals, sorted by net worth (largest to smallest)
•	Built a second pivot table to count the number of billionaires by age group (grouped in 10-year intervals from 30 to 100)
•	Found that the 60–80 age group had the highest concentration of billionaires

## 3. Data Visualization
•	Added slicers to filter the pivot tables dynamically by industry/category, self-made status, and gender
•	Linked slicers to both pivot tables using Report Connections so filters applied across all visuals
•	Created a clustered column chart showing net worth of the Top 10 billionaires
•	Created a second clustered column chart showing billionaire count by age group, which revealed a bell curve peaking between ages 50 and 90

## Tools Used
•	Microsoft Excel
•	Data Analysis ToolPak
•	Pivot Tables & Slicers


