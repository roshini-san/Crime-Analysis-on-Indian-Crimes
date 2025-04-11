 # Crime-Analysis-on-Indian-Crimes

![Screenshot 2025-03-08 125018](https://github.com/user-attachments/assets/f2d8ddec-4e44-4bc1-a149-b85f6f1f8b16)

This project leverages data visualization and analytics to identify crime trends across Indian cities using Power BI dashboards and R. It provides insights into crime types, victim demographics, and city-wise patterns to support law enforcement and policy-making.

Introduction

Crime is a persistent issue that affects the safety and well-being of citizens. This project aims to offer a comprehensive view of crime data across Indian cities using dynamic dashboards created with Power BI and data processed through R. The objective is to identify patterns in criminal activities based on city, time, weapon used, victim's age and gender, and other variables. These insights can help authorities deploy resources more effectively, raise public awareness, and implement targeted crime prevention strategies. The visualization also empowers analysts and researchers to explore data interactively and extract meaningful conclusions.



Data Collection and Description

The data used in this project consists of crime records from various cities across India from
2020 to 2024. It includes detailed information about the type of crime, the date and time of
occurrence, the weapon used, victim demographics, and the level of police deployment.
The data also includes information on whether the case was closed, providing a clear view
of crime resolution rates across cities.
Data Preprocessing Steps
● Converted Date Reported into date format.
● Extracted year, month, and day for trend analysis.
● Cleaned and transformed time-of-occurrence data.


📦 Dependencies
Make sure you have the following installed:

Power BI Desktop (version 2.127.1326.0 or later recommended)
R (version 4.0+)
OS: Windows 10 or later
Required R Packages:
readxl
dplyr
ggplot2
lubridate

Installing

Clone the project repository or download the .pbix Power BI file and supporting .xlsx data files.
Ensure R is integrated with Power BI:
Power BI ➝ File ➝ Options ➝ R Scripting ➝ Set R home directory.
Open the Power BI file and allow it to connect with R script if prompted.


Step-by-step:
-Load the Dataset
 Open the Power BI file (Crime_Analysis.pbix).
 Ensure the Excel data source is properly mapped.
-Refresh Data
 Click Home ➝ Refresh to run the latest R script and reload the visualizations.
-Explore Dashboards
 -Navigate between the pages for:
  City-wise crime trends
  Victim demographics
  Time of report
  Weapon usage
  Police deployment stats

![Screenshot 2025-02-22 142723](https://github.com/user-attachments/assets/af5a4bfe-3849-4681-b88f-e52943615594)

Code Block Example
To install R dependencies:

install.packages(c("readxl", "dplyr", "ggplot2", "lubridate"))


Help
 
If you see a "R script error" in Power BI:
Check that R is installed and correctly mapped in Power BI settings.
"Data Source Error":
Go to Transform Data ➝ Data Source Settings, and re-map the Excel file location.


Authors

Roshini S - roshinisanthakumar@gmail.com
